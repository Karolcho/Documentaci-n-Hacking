# Descripción
How well can you perfom basic binary operations? Start searching for the flag here `nc titan.picoctf.net 58746`

# Solución
Conectarnos a la página indicada, después tener conocimiento básico para operaciones con binarios, e ir resolviendo poco a poco las preguntas que se nos indican hasta obtener la flag

- Utilizar el webshell integrado, después conectarnos a la página que nos indica, luego ir avanzando poco a poco con los dos número s que se nos entregan, primero es hacer un desplazamiento hacia la izquierda del primer binario, después es hacer una comparación Or entre ambos binarios, luego hacer una suma entre ambos binarios, luego aplicar un desplazamiento hacia la derecha del segundo binario, luego una comparación And entre ambos y por último una multiplicación entre ambos binarios, a este último se convierte en hexadecimal y con ello obtenemos la flag correspondiente

picoCTF{b1tw^3se_0p3eR@tI0n_su33essFuL_d6f8047e}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/