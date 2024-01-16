cmake_minimum_required (VERSION 3.20)

project (cpp-template)

add_subdirectory ("src")

# For clangd lsp server
file(CREATE_LINK
    "${CMAKE_BINARY_DIR}/compile_commands.json"
    "${CMAKE_SOURCE_DIR}/build/compile_commands.json"
    SYMBOLIC
)
