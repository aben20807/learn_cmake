add_library(
    say_hello SHARED
    src/say_hello_util/hello.cpp
)

target_include_directories(say_hello PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/src")