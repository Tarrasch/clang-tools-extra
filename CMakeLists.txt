add_subdirectory(remove-cstr-calls)
add_subdirectory(tool-template)
add_subdirectory(clang-format)
add_subdirectory(cpp11-migrate)

# Add the common testsuite after all the tools.
add_subdirectory(test)
