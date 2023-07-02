cmake_minimum_required(VERSION 3.10.2)

project(CI)

add_executable(${PROJECT_NAME} 
                main.c 
                chunk.c 
                memory.c 
                debug.c 
                value.c 
                vm.c
                compiler.c
                scanner.c)