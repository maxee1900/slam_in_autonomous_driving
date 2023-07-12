# 编译时可指定特定可执行文件 `make motion`
add_executable(motion motion.cc)
# 库名称可以起不同的后缀
target_link_libraries(motion
        ${PROJECT_NAME}.common
        ${PROJECT_NAME}.tools
        )
