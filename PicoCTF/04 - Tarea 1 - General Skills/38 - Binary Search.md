# Descripción
Want to play a game? As you use more of the shell, you might be interested in how they work! Binary search is a classic algorithm used to quickly find an item in a sorted list. Can you find the flag? You'll have 1000 possibilities and only 10 guesses. Cyber security often has a huge amount of data to look through - from logs, vulnerability reports, and forensics. Practicing the fundamentals manually might help you in the future when you have to write your own tools! You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_atlas/17/challenge.zip)

`ssh -p 56802 ctf-player@atlas.picoctf.net` Using the password `f3b61b38`. Accept the fingerprint with `yes`, and `ls` once connected to begin. Remember, in a shell, passwords are hidden!
# Solución
Usando ssh conectarnos a la pagina con el usuario y contraseña indicados, después utilizar búsqueda binaria para conseguir la flag

- Utilizar el webshell integrado, después conectarnos a la página que nos indica, luego solo ir aplicando sumas o restas en base a la búsqueda binaria, siempre ir a la mitad, ya sea mayor o menor del número indicado hasta obtener la flag

picoCTF{g00d_gu355_6dcfb67c}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
- Podría crearse un script para ir haciendo de manera automática las operaciones hasta obtener el flag
# Referencias
- https://webshell.picoctf.org/