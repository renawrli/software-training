add_executable(week4 starter_main.cpp)
add_dependencies(week4 STSL)
target_link_libraries(week4 ${STSL_LIBS})

add_executable(week4_final final_main.cpp)
add_dependencies(week4_final STSL)
target_link_libraries(week4_final ${STSL_LIBS})
