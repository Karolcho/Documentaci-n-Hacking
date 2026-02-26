# Descripción
Can you find the flag on this website. Try to find the flag [here](http://saturn.picoctf.net:53484/).
# Solución
Acceder al link dado, después aplicar inyecciones SQL hasta conseguir la flag

- Primero es entrar al link que se nos da, después se aplica una inyección de 'or 1=1; para pasar el login, luego al entrar usamos otra inyección para checar las tablas que hay y al observar la que contiene el campo flag solamente le usamos un ' union select id,flag,3 from more_table; para con ello poder obtener la flag

picoCTF{G3tting_5QL_1nJ3c7I0N_l1k3_y0u_sh0ulD_62aa7500}


# Notas adicionales
- 
# Referencias
- 