# ESP32 UART Bridge

ESP32 code for enable the access to a UART access from a Wi-Fi server running on the ESP32 device.

> ⚠️ DO NOT USE IT IN PRODUCTION ⚠️
> Please, since the network is NOT encrypted (even when using a WPA3 Wi-Fi) and the server does not implement a secure authentication, do **NOT** use it in production!
> 
> To use it in production, fork the code and code a SSH server. I wait your pull request.

This Arduino code is based on the [faydr's QMesh-ESP32](https://github.com/faydr/QMesh-ESP32/blob/main/qmesh_interface/qmesh_interface.ino)
