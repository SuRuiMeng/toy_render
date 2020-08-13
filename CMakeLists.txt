# CMakeList.txt: toy_render 的 CMake 项目，在此处包括源代码并定义
# 项目特定的逻辑。
#
cmake_minimum_required (VERSION 3.8)

project ("toy_render")

# 将源代码添加到此项目的可执行文件。
# 包含子项目。
add_subdirectory(support)
add_subdirectory (render)
# TODO: 如有需要，请添加测试并安装目标。
