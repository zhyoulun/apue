cmake_minimum_required(VERSION 3.17)
project(apue001 C)

set(CMAKE_C_STANDARD 99)

include_directories(/Users/zhangyoulun/codes/github/apue/apue.3e/include)
link_directories(/Users/zhangyoulun/codes/github/apue/apue.3e/lib)

add_executable(apue001 main.c)

target_link_libraries(apue001
        /Users/zhangyoulun/codes/github/apue/apue.3e/lib/libapue.a
        )