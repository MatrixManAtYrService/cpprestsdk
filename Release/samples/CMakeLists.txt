add_subdirectory(SearchFile)
add_subdirectory(BingRequest)
add_subdirectory(BlackJack)
add_subdirectory(Oauth1Client)
add_subdirectory(Oauth2Client)
add_subdirectory(HelloWorld)

add_custom_target(samples
  DEPENDS SearchFile BingRequest blackjackclient blackjackserver helloworldlistener helloworldspeaker oauth1client oauth2client
  )
