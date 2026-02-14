# Descripción
Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/17/level3.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/17/level3.flag.txt.enc) and the [hash](https://artifacts.picoctf.net/c/17/level3.hash.bin) in the same directory too. There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.
# Solución
Descargar los archivos indicados, después abrir el checador, obtener con ello la contraseña y utilizarla para conseguir la flag

- Utilizar el webshell integrado, después descargar los tres archivos indicados, luego abrir el checador con cat, luego se nos da alli un total de 7 contraseñas, ir aplicando cada una, hasta encontrar la correcta que fue "87ab", luego abrimos de nuevo el checador pero ahora con python, introducimos contraseña y con ello obtenemos la flag

picoCTF{m45h_fl1ng1ng_cd6ed2eb}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/