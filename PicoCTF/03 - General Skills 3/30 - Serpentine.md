# Descripción
Find the flag in the Python script! [Download Python script](https://artifacts.picoctf.net/c/36/serpentine.py)
# Solución
Descargar el archivo indicado, después abrirlo utilizando nano, corregir la condicional y volver a ejecutarlo con python para conseguir la flag

- Utilizar el webshell integrado, después descargar el archivo .py que se nos da, a este aplicarle nano para poder ver el código, cambiar el condicional de cuando se escribe b su función para que mande a llamar a "print_flag()", luego de editar eso ejecutarlo con python y solamente escribir b y obtener la flag

picoCTF{7h3_r04d_l355_7r4v3l3d_aa2340b2}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
- Puede editarse el código para que solamente nos de la flag directamente sin necesidad de lo demás
- Puede utilizarse directamente el cyberchef y mandarle la flag encriptada
# Referencias
- https://webshell.picoctf.org/