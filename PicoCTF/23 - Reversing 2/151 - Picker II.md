# Descripción
Can you figure out how this program works to get the flag? Connect to the program with netcat: `$ nc saturn.picoctf.net 56477` The program's source code can be downloaded [here](https://artifacts.picoctf.net/c/521/picker-II.py).
# Solución
Pasar el mini filtro y usar de nuevo win para obtener la flag

- Primero descargamos el código que se nos da y además entramos a la página indicada, como podemos observar agregaron un filtro para no escribir directamente win, pero si simplemente lo pasamos con "globals()['w' + 'in']", podemos pasar el filtro y luego lo que nos da lo traducimos de hexadecimal y conseguimos la flag

picoCTF{f1l73r5_f41l_c0d3_r3f4c70r_m1gh7_5ucc33d_b924e8e5}


# Notas adicionales
- 
# Referencias
- https://gchq.github.io/CyberChef/#recipe=From_Hex('Auto')&input=MHg3MCAweDY5IDB4NjMgMHg2ZiAweDQzIDB4NTQgMHg0NiAweDdiIDB4NjYgMHgzMSAweDZjIDB4MzcgMHgzMyAweDcyIDB4MzUgMHg1ZiAweDY2IDB4MzQgMHgzMSAweDZjIDB4NWYgMHg2MyAweDMwIDB4NjQgMHgzMyAweDVmIDB4NzIgMHgzMyAweDY2IDB4MzQgMHg2MyAweDM3IDB4MzAgMHg3MiAweDVmIDB4NmQgMHgzMSAweDY3IDB4NjggMHgzNyAweDVmIDB4MzUgMHg3NSAweDYzIDB4NjMgMHgzMyAweDMzIDB4NjQgMHg1ZiAweDYyIDB4MzkgMHgzMiAweDM0IDB4NjUgMHgzOCAweDY1IDB4MzUgMHg3ZCA