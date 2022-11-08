# Common commands in CMD-Batch

- Matar un Proceso

``taskkill /F /FI "SERVICES eq yourservice"``

- Parar un servicio

``SC STOP "servicename"``

- Encontrar PID de un servicio

``sc queryex servicename``

- Matar servicio por PID

``taskkill /f /pid [PID]``

- See DNS cache

``ipconfig/displaydns``


- Clear DNS cache

``ipconfig/flushdns``

- Search a file name within a directory
`dir "search term*" /s`