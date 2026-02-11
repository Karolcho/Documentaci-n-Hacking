# Descripción
There's an interesting script in the user's home directory The work computer is running SSH. We've been given a script which performs some basic calculations, explore the script and find a flag.
```
Hostname: saturn.picoctf.net
Port:     61851
Username: picoplayer
Password: password
```
# Solución
Conectarnos a la pagina indicada con su usuario y contraseña, después aplicar un man en el archivo useless y conseguir la flag

- Utilizar el webshell integrado y conectarnos con los datos que se nos proporcionaron, después comprobar el contenido del archivo con un cat, luego utilizar un man para ver el manual de la función y con ello se encuentra la flag

picoCTF{us3l3ss_ch4ll3ng3_3xpl0it3d_3823}


# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/