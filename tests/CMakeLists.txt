target_sources(${BUILD_NAME} PRIVATE
    catch_cpp_tlc5955.cpp
    tlc5955_tester.cpp
)

target_include_directories(${BUILD_NAME} PRIVATE 
    .
)