# Descripción
Files can always be changed in a secret way. Can you find the flag? [cat.jpg](https://challenge-files.picoctf.net/c_wily_courier/76e95e3e6ee69b4f82b3cea25051f5a9a5918b57809a1f90b29b06b776c73bc7/cat.jpg)
# Solución
Descargar la imagen y usar la herramienta exiftool para obtener la flag

- Primero descargamos la imagen, después usamos exiftool para ver los metadatos y copiamos la parte de licencia para flag encriptada, usamos cyberchef y con eso obtenemos la flag

picoCTF{the_m3tadata_1s_modified}


# Notas adicionales
- 
# Referencias
- https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9-_',true,false)&input=Y0dsamIwTlVSbnQwYUdWZmJUTjBZV1JoZEdGZk1YTmZiVzlrYVdacFpXUjk