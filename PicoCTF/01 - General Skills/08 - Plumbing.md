# Descripción
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag?
Connect to fickle-tempest.picoctf.net 53951.
# Solución
Conectarnos a la pagina y port indicados pero utilizar in pipline para aplicar a la vez un grep

- Utilizar el webshell integrado y utilizar el comando "nc fickle-tempest.picoctf.net 53951 | grep picoCTF"

picoCTF{digital_plumb3r_d3246b6B}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/