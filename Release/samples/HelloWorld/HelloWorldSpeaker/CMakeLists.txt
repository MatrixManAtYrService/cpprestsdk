add_executable(helloworldspeaker
  speak.cpp
  )

target_link_libraries(helloworldspeaker ${Casablanca_LIBRARIES})
set_target_properties(helloworldspeaker PROPERTIES LINKER_LANGUAGE CXX)

