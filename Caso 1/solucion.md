# Solución
Se detectó que el equipo tenía una configuración incorrecta del servidor DNS.

Se realizan los siguentes pasos para su correcion 

#1 Se tiene que abrir la configuracion de red.
#2 Se accede a las propiedades del adaptador
#3 Se configura de manera manual el servidor DNS

DNS Primario:
8.8.8.8

DNS Secundario:
8.8.4.4

luego se le verifica la conexion con: 

ping google.com
nslookup google.com

Y la conexion a internet se restaura correctamente.
