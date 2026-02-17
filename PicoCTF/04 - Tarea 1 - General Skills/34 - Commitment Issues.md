# Descripción
I accidentally wrote the flag down. Good thing I deleted it! You download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/137/challenge.zip)
# Solución
Descargar el archivo indicado, después con git, hacer un control de versiones, volviendo a antes de borrar la flag. Con ello obtener la flag

- Utilizar el webshell integrado, después descargar el .zip y descomprimirlo, luego entramos a la carpeta y apoyandonos de git, volvemos al commit antes de que se borrara la flag y la restauramos, aplicando un "git checkout ea859bf3b5d94ee74ce5ee1afa3edd7d4d6b35f0", ahora ya en esa versión simplemente aplicamos un cat al txt y obtenemos la flag

picoCTF{s@n1t1z3_cf09a485}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/