# Descripción
Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `8c606eb1` on the host `wily-courier.picoctf.net` and port `55987`.
# Solución
Conectarse a la pagina indicada, después ir recorriendo las diversas carpetas para poco a poco según las instrucciones ir aplicando cat y ir obteniendo la flag

- Utilizar el webshell integrado, después conectarse a la pagina como el usuario indicado, luego aplicar un cat a los primeros dos archivos y seguir las instrucciones, luego acceder a la "/" alli aplicar cat a la siguiente parte de la flag y las instrucciones y por último dirigirte a "~" y obtener la última parte de la flag

picoCTF{xxsh_0ut_0f_//4t3r_0b24fc4f}


# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/