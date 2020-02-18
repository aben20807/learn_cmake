add_library(
    sum
    src/sum/sum.cpp
)

target_include_directories(sum PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/include")