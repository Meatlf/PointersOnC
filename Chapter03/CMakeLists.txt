cmake_minimum_required(VERSION 3.0.0)
project(Chapter01 VERSION 0.1.0)


#dubug 模式
set (CMAKE_C_FLAGS  "${CMAKE_C_FLAGS} -g")

# 添加头文件路径
# include_directories("${PROJECT_SOURCE_DIR}/project0")
# include_directories("${PROJECT_SOURCE_DIR}/project1")
# include_directories("${PROJECT_SOURCE_DIR}/project2")
# include_directories("${PROJECT_SOURCE_DIR}/exercise1")

# add_executable(test_project0 ./usett0.cpp)
# add_executable(test_project1 ./usett1.cpp)
# add_executable(project2_test ./usebrass2.cpp)
add_executable(exercise01 ./exercise01.c)

# 添加子目录
# add_subdirectory(project0)
# add_subdirectory(project1)
# add_subdirectory(project2)
# add_subdirectory(exercise1)

# 添加project0库
# target_link_libraries(test_project0 project0)
# target_link_libraries(test_project1 project1)
# target_link_libraries(project2_test project2)
# target_link_libraries(exercise1_test exercise1)

# set(CPACK_PROJECT_NAME ${PROJECT_NAME})
# set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
# include(CPack)
