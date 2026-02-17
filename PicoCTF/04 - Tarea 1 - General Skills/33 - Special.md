# Descripción
Don't power users get tired of making spelling mistakes in the shell? Not anymore! Enter Special, the Spell Checked Interface for Affecting Linux. Now, every word is properly spelled and capitalized... automatically and behind-the-scenes! Be the first to test Special in beta, and feel free to tell us all about how Special streamlines every development process that you face. When your co-workers see your amazing shell interface, just tell them: That's Special (TM) Start your instance to see connection details.
`ssh -p 50301 ctf-player@saturn.picoctf.net` The password is `483e80d4`
# Solución
Usando ssh conectarnos a la pagina con el usuario y contraseña indicados, luego utilizar "${parameter:=}" para hacer diversas acciones y obtener la flag

- Utilizar el webshell integrado, después con el ssh acceder a la página con el usuario indicado, luego con la documentación del Shell Parameter Extension intentar un "${parameter:=ls}" para ver que archivos hay, luego se puede observar blargh que es un directorio, por lo que luego se aplica un ${parameter:=ls blargh}, con esto observamos que tiene dentro "flag.txt", por lo que por último aplicamos ${parameter:=cat blargh/flag.txt} y con ello obtenemos la flag

picoCTF{5p311ch3ck_15_7h3_w0r57_b741d1b1}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/