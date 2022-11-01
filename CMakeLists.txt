project(pesq)

aux_source_directory(. SRC_MAIN)

add_executable(${PROJECT_NAME} 
               ${SRC_MAIN})

target_include_directories(${PROJECT_NAME}
                            PUBLIC
                            .
)