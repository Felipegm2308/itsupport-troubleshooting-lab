# Servicio del sistema detenido

Problema: Servicio de impresion no funciona.

Diagnostico:

Se abre services.msc y se busca Print Spooler:

Se revisan logs en Event viewer y se utiliza el comando:
Sc query spooler y se da la solucion net stop spooler
net start spooler
