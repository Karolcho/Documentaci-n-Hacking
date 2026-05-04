# Descripción
Can you figure out how this program works to get the flag? Connect to the program with netcat: `$ nc saturn.picoctf.net 60144` The program's source code can be downloaded [here](https://artifacts.picoctf.net/c/527/picker-IV.c). The binary can be downloaded [here](https://artifacts.picoctf.net/c/527/picker-IV).
# Solución
Acceder a los binarios y conseguir lo que da el win para tener la flag

- Primero descargamos los archivos en la terminal de pico, después solamente aplicamos el comando "nm picker-IV | grep win", con eso lo que nos de nos quedamos únicamente con los últimos caracteres, accedemos a la página y los colocamos para conseguir la flag

picoCTF{n3v3r_jump_t0_u53r_5uppl13d_4ddr35535_01672a61}


# Notas adicionales
- 
# Referencias
- 