cmake_minimum_required(VERSION 3.20)
project(Github)

set(CMAKE_CXX_STANDARD 14)

add_executable(Github
        .idea/codeStyles/codeStyleConfig.xml
        .idea/codeStyles/Project.xml
        .idea/.gitignore
        .idea/Github.iml
        .idea/modules.xml
        .idea/vcs.xml
        .idea/workspace.xml
        .clang-format
        test.cpp)
