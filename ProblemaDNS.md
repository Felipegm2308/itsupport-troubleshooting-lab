# Problema de DNS

En este diagnostico el Usuario puede realizar ping a la direccion IP pero no al dominio.

Diagnostico:
Ping 8.8.8.8

Funciona:
Ping google.com

Falla:
nslookup google.com

Resultado:
El servidor DNS no responde.

Solucion:
ip config /flushdns
ip config /release
ip config /renew
