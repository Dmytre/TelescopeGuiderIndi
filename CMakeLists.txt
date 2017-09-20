include_directories( /usr/include/libindi )

add_executable(simpledevice_drv simpledevice.cpp)
target_link_libraries(simpledevice_drv indidriver)
target_link_libraries(simpledevice_drv z)
target_link_libraries(simpledevice_drv nova)
