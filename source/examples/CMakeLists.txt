
# Check if examples are enabled
if(NOT OPTION_BUILD_EXAMPLES)
    return()
endif()

# Example applications
add_subdirectory(logging)
add_subdirectory(cmdline)
add_subdirectory(io)
add_subdirectory(simd)
