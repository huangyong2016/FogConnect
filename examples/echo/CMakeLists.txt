

add_executable(echo_server server.c)
target_link_libraries(echo_server 
                      fog_connection
                      event
                      glib-2.0)



add_executable(echo_client client.c)
target_link_libraries(echo_client 
                      fog_connection
                      event
                      glib-2.0)


