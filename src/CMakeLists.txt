
# 定义项目名称
set(PROJECT_NAME RTTheNextWeekendAoPractise)
# 低版本以及policy不允许使用版本号
cmake_minimum_required(VERSION 3.0)
cmake_policy(SET CMP0048 NEW)
# 设置项目版本号
set(PROJECT_VERSION 0.1)
# 设置项目信息
project(${PROJECT_NAME} VERSION ${PROJECT_VERSION})

add_subdirectory(Chapter2MotionBlur)



