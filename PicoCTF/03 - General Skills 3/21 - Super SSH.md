# Descripción
Using a Secure Shell (SSH) is going to be pretty important. Can you `ssh` as `ctf-player` to `titan.picoctf.net` at port `59763` to get the flag? You'll also need the password `6dd28e9b`. If asked, accept the fingerprint with `yes`. If your device doesn't have a shell, you can use: [https://webshell.picoctf.org](https://webshell.picoctf.org/) If you're not sure what a shell is, check out our Primer: 
# Solución
Usando ssh conectarnos a la pagina con el usuario y contraseña indicados y obtener la flag

- Utilizar el webshell integrado, después con el comando ssh conectarnos a la pagina con el usuario de crf-player y su contraseña y con ello nos devuelve la flag

picoCTF{s3cur3_c0nn3ct10n_5d09a462}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/