cmake_minimum_required(VERSION 3.16.3)
project(C)

set(CMAKE_C_STANDARD 99)

add_executable(main3 lab3/main3.c lab3/table.c lab3/keyspace1.c lab3/keyspace2.c)
add_executable(main3b lab3b/main3.c lab3b/tableBuf.c lab3b/keySp1buf.c lab3b/keySp2buf.c)
add_executable(main4b lab4b/RBTree.c)
#add_executable(main3btest lab3b/tableBuf.c)
add_executable(3b 3b/3b 3b/table.c)
add_executable(que lab2/Queue.c lab2/main.c)