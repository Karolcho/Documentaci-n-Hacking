# Descripción
We found this weird message being passed around on the servers, we think we have a working decryption scheme. Download the message [here](https://artifacts.picoctf.net/c/129/message.txt). Take each number mod 37 and map it to the following character set: 0-25 is the alphabet (uppercase), 26-35 are the decimal digits, and 36 is an underscore. Wrap your decrypted message in the picoCTF flag format (i.e. `picoCTF{decrypted_message}`)
# Solución
Crear un código para desencriptar el mensaje dado y obtener la flag

- Primero descargamos el archivo que se nos da, después apoyándonos en colab, hacemos un código que simplemente aplique a los números un mod 37, además de indicarle los caracteres permitidos, con ello lo ejecutamos y obtenemos la flag

picoCTF{R0UND_N_R0UND_ADD17EC2}


# Notas adicionales
- 
# Referencias
- https://colab.research.google.com/drive/1FvQedyxNKOHvxBKPd37f3N2yVUsSKfnG?usp=sharing