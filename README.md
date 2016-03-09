# escaner-de-redes
Es un script Bash basado en nmap para escanear constantemente las redes y alertar de nuevas conexiones
Se abre un terminal en la carpeta de descarga y se escribe sh redes.sh
El script hace un primer escaneo de las redes y le pide al usuario que identifique las direcciones ip de sus equipos conectados.
Estas direcciones seran excluidas y cada 3 segundos nmap escaneará en busca de nuevas direcciones, si hay algún cambio en la red se avisará al usuario mediante una ventana emergente.
Si el usuario conoce la nueva conexión tiene la opción de seguir escaneando la red, de lo contrario puede seleccionar la opción de un escaneo mas profundo para tener mas información de los equipos conectados a la red
