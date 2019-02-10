add_executable(ill_example_run 
    main.cpp)

set_target_properties(ill_example_run PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED YES
    CXX_EXTENSIONS NO
)

target_link_libraries(ill_example_run PRIVATE ill_example)
