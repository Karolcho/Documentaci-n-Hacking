# Descripción
This website can be rendered only by picobrowser, go and catch the flag! http://fickle-tempest.picoctf.net:55661
# Solución
Usando curl, conectarnos a la página indicada, dando de usuario a picobrowser para obtener la flag

- Utilizar el webshell integrado, después colocar "curl" y el link de la página pero agregar "-H "User-Agent: picobrowser", para con ello acceder como picobrowser y obtener la flag

picoCTF{p1c0_s3cr3t_ag3nt_fba5c48f}


# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/