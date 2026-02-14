# Descripción
Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/13/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/13/level2.flag.txt.enc) in the same directory too.
# Solución
Descargar los archivos indicados, después abrir el checador, obtener con ello la contraseña y utilizarla para conseguir la flag

- Utilizar el webshell integrado, después descargar los dos archivos indicados, luego abrir el checador con cat, con ello se puede ver la contraseña encriptada con hexadecimal, por lo que utilizando cyberchef la desencriptamos para obtenerla, luego abrimos de nuevo el checador pero ahora con python, introducimos contraseña y con ello obtenemos la flag
https://gchq.github.io/CyberChef/#recipe=From_Hex('Space')&input=NjQgNjUgMzcgMzY

picoCTF{tr45h_51ng1ng_489dea9a}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/
- https://gchg.github.io/CyberChef