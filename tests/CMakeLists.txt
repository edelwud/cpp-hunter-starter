file(GLOB_RECURSE TEST_SOURCE *.cpp)
add_executable(test_${PROJECT_NAME} ${TEST_SOURCE})

find_package(GTest)
target_link_libraries(test_${PROJECT_NAME} GTest::GTest)