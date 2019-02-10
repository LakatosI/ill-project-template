add_library(ill_example STATIC
    example.cpp)

set_target_properties(ill_example PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED YES
    CXX_EXTENSIONS NO
)

target_include_directories(ill_example PUBLIC ${PROJECT_SOURCE_DIR}/include)
