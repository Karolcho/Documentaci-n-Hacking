# Descripción
Do you know how to use the web inspector? Start searching [here](http://titan.picoctf.net:60038/) to find the flag
# Solución
Entrar a la página, inspeccionarla y encontrar la flag codificada, luego solamente decodificarla

- Primero es entrar a la página, luego es entrar al apartado de about, allí inspeccionar el código y encontrar la flag codificada "cGljb0NURnt3ZWJfc3VjYzNzc2Z1bGx5X2QzYzBkZWRfMWY4MzI2MTV9", luego la mandamos a cyberchef y conseguimos la flag

picoCTF{web_succ3ssfully_d3c0ded_1f832615}


# Notas adicionales
- 
# Referencias
- https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=Y0dsamIwTlVSbnQzWldKZmMzVmpZek56YzJaMWJHeDVYMlF6WXpCa1pXUmZNV1k0TXpJMk1UVjk