# Descripción
How to automate tasks to run at intervals on linux servers? Use ssh to connect to this server:

```
Server: saturn.picoctf.net
Port: 58387
Username: picoplayer 
Password: bLgSMmbY6X
```
# Solución
Usando ssh conectarnos a la pagina con el usuario y contraseña indicados, luego utilizar el crontab y obtener la flag

- Utilizar el webshell integrado, después con el ssh acceder a la página con el usuario indicado y con el comando "crontab", utilizar "cat /etc/crontab" para con ello obtener la flag

picoCTF{Sch3DUL7NG_T45K3_L1NUX_1b4d8744}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/