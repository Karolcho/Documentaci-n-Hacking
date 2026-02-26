# Descripción
Check the admin scratchpad! http://fickle-tempest.picoctf.net:61883
# Solución
Entrar a la página indicada, después con ayuda de el comando john, crackear la cookie y al reenviarla conseguir la flag

- Primero es entrar al link que se nos indica, luego con el cookie editor, conseguimos la cookie que da al loguearnos y la editamos para que el user sea admin, luego esa cookie la guardamos en un archivo "hash" y utilizando el john la crackeamos para conseguir la firma, luego agregamos ambas cosas y eso nos devuelve la cookie que funciona, la introducimos en la página y obtenemos la flag

picoCTF{jawt_was_just_what_you_thought_bbb82bd4a57564aefb32d69dafb60583}


# Notas adicionales
- 
# Referencias
- 