# Descripción
Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/12/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/12/level1.flag.txt.enc) in the same directory too.
# Solución
Descargar los archivos indicados, después abrir el checador, obtener con ello la contraseña y utilizarla para conseguir la flag

- Utilizar el webshell integrado, después descargar los dos archivos indicados, luego abrir el checador con cat, con ello se puede ver la contraseña que se necesita para poder desencriptar la flag, por lo que abrimos de nuevo el checador pero ahora con python, introducimos contraseña y con ello obtenemos la flag

picoCTF{545h_r1ng1ng_1b2fd683}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/