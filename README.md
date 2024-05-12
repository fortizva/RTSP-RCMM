# RCMM Laboratorio 06 - RTSP
Este proyecto de laboratorio se enfoca en la creación de una conexión servidor-cliente utilizando RTCP
para la transmisión multimedia en tiempo real. El objetivo es comprender cómo funciona RTCP y desarrollar
 habilidades prácticas en la configuración y gestión de conexiones multimedia en tiempo real.
 
## Cómo ejecutar el proyecto
Para ejecutar el proyecto será necesario ***ejecutar el servidor y el cliente en ese orden***, además de usar
los siguientes parámetros de lanzamiento:

###### Servidor
`java -jar Servidor <server_port>`

###### Cliente
`java -jar Cliente <server_ip> <server_port> <media_path> [-v]`

Es importante el orden de los parámetros. Además, `media_path` debe ser una ruta, absoluta o relativa desde la ruta de ejecución del servidor, que apunte a 
un fichero de vídeo o audio soportado.