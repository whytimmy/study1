add_executable(list_tests test_list.cpp)

target_link_libraries(list_tests
	gtest_main 
	gmock_main
	scl_lib
)

add_test(list_tests list_tests)
