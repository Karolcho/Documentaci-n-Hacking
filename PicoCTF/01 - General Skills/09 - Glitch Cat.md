# Descripción
Our flag printing service has started glitching! `$ nc saturn.picoctf.net 61986`
# Solución
Conectarnos a la pagina y port indicados, lo que nos da, tenemos que usarlo en la terminal abriendo python y al pegarlo directamente para que de la respuesta

- Utilizar el webshell integrado y utilizar el comando "nc saturn.picoctf.net 61986", eso nos da lo siguiente: 'picoCTF{gl17ch_m3_n07_' + chr(0x39) + chr(0x63) + chr(0x34) + chr(0x32) + chr(0x61) + chr(0x34) + chr(0x35) + chr(0x64) + '}'
  Ya una vez con ese texto al introducirlo en la terminal con python nos da la flag.

picoCTF{gl17ch_m3_n07_9c42a45d}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/