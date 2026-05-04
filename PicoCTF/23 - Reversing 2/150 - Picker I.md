# Descripción
This service can provide you with a random number, but can it do anything else? Connect to the program with netcat: `$ nc saturn.picoctf.net 55226` The program's source code can be downloaded [here](https://artifacts.picoctf.net/c/514/picker-I.py).
# Solución
Descargar el código dado y en la terminal acceder y introducir el comando para obtener la flag

- Primero descargamos el código que se nos da y accedemos a la página indicada, luego de analizar el código se puede ver que escribiendo la palabra win, nos ejecuta la acción para conseguir la flag cifrada, luego únicamente la desciframos de hexadecimal y obtenemos la flag

picoCTF{4_d14m0nd_1n_7h3_r0ugh_6e04440d}


# Notas adicionales
- 
# Referencias
- https://gchq.github.io/CyberChef/#recipe=From_Hex('Auto')&input=MHg3MCAweDY5IDB4NjMgMHg2ZiAweDQzIDB4NTQgMHg0NiAweDdiIDB4MzQgMHg1ZiAweDY0IDB4MzEgMHgzNCAweDZkIDB4MzAgMHg2ZSAweDY0IDB4NWYgMHgzMSAweDZlIDB4NWYgMHgzNyAweDY4IDB4MzMgMHg1ZiAweDcyIDB4MzAgMHg3NSAweDY3IDB4NjggMHg1ZiAweDM2IDB4NjUgMHgzMCAweDM0IDB4MzQgMHgzNCAweDMwIDB4NjQgMHg3ZA