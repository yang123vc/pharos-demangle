find_package(Boost 1.60.0 REQUIRED)

add_executable(demangle demangle.cpp)
target_link_libraries(demangle libdemangle)