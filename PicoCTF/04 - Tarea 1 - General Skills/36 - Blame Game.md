# Descripción
Someone's commits seems to be preventing the program from working. Who is it? You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/158/challenge.zip)
# Solución
Descargar el archivo indicado, después con git, comprobar el historial del archivo .py y con ello conseguir la flag

- Utilizar el webshell integrado, después descargar el .zip y descomprimirlo, luego entrar a la carpeta de drop in y alli aplicar un git log pero al archivo "message.py" para filtrar, con ello se obtiene la flag al ver el usuario que hizo el commit

picoCTF{@sk_th3_1nt3rn_2c6bf174}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/