function(executors_add_example EXENAME)
  add_executable(${EXENAME} ${EXENAME}.cpp)
  target_link_libraries(${EXENAME} executors)
endfunction(executors_add_example)

add_subdirectory(actor)
add_subdirectory(adapter)
add_subdirectory(async)
add_subdirectory(async_ops)
add_subdirectory(for_each)
add_subdirectory(properties)
add_subdirectory(inline)
add_subdirectory(invoke)
add_subdirectory(nested)
add_subdirectory(simple)
add_subdirectory(pipeline)
