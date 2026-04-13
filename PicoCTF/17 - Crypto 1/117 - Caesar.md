# Descripción
Decrypt this message. Message: [message](https://challenge-files.picoctf.net/c_fickle_tempest/4baa3e051f746434453e7cb328af49573b3771c7789d068c0c53df5c52919a5b/data.enc)
# Solución
Descargar el archivo que se nos da y usar ROT13 para conseguir la flag

- Primero descargamos el archivo que se nos da, después utilizamos el texto y lo mandamos a cyberchef, luego le aplicamos ROT13 y le agregamos que gire más veces un total de 27 para poder obtener nuestra flag

picoCTF{crossingtherubiconqilhsxrk}


# Notas adicionales
- 
# Referencias
- https://gchq.github.io/CyberChef/#recipe=ROT13(true,true,false,27)&input=YnFucnJobWZzZ2RxdGFoYm5tcGhrZ3J3cWo