set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}/bin")

add_executable(main main.cc)
target_compile_features(main PUBLIC cxx_std_23)