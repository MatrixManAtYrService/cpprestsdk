add_executable(helloworldlistener
  listen.cpp
  )

target_link_libraries(helloworldlistener ${Casablanca_LIBRARIES})
set_target_properties(helloworldlistener PROPERTIES LINKER_LANGUAGE CXX)
