# CMake 最低版本号要求
cmake_minimum_required (VERSION 2.8)

# 项目信息
project (client-server-cpp)

# 查找当前目录下的所有源文件
# 并将名称保存到 DIR_SRCS 变量
aux_source_directory(src DIR_SRCS)

# 指定生成目标
add_executable(client-server-cpp ${DIR_SRCS})