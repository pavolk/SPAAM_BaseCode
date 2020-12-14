


find_package(LAPACK REQUIRED)

add_executable(spaam_tool_original SPAAM_Code.cpp)
target_link_libraries(spaam_tool_original ${LAPACK_LIBRARIES})
