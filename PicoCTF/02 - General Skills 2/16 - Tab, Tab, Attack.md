# Descripción
Using tabcomplete in the Terminal will add years to your life, esp. when dealing with long rambling directory structures and filenames.
# Solución
Descomprimir el archivo .zip, llegar hasta el último nivel de carpetas y aplicar al archivo encontrado un strings junto un grep y obtener la flag

- Utilizar el webshell integrado después aplicar un cd y ir autocompletando cada nivel con tab, luego al archivo del final aplicarle un strings junto con un pipe que añada el grep picoCTF y se obtiene la flag

picoCTF{l3v3l_up!_t4k3_4_r35t!_fc588427}


# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/