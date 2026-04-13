# Descripción
Can you get the real meaning from this file. Download the file [here](https://artifacts.picoctf.net/c_titan/108/enc_flag).
# Solución
Ir decodificando la flag poco a poco hasta conseguirla

- Primero descargamos el archivo que se nos da, después el texto lo introducimos en cyberchef con base64, luego lo que nos da lo volvemos a introducir y por ultimo nos apoyamos de ROT13 pero con 19 rotaciones para conseguir la flag

picoCTF{caesar_d3cr9pt3d_a47c6d69}


# Notas adicionales
- 
# Referencias
- https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=WWlka00wSnhaR3R3UWxSWWRIRmhSM2cyWVVoc1ptRjZUbkZsVkd3eldWUk9jbGd5WnpCT01tOHlZWHBaTldaUlBUMG5DZz09Cg
- https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=ZDNCcWRrcEJUWHRxYUd4NmFIbGZhek5xZVRsM1lUTnJYMmcwTjJvMmF6WTVmUT09
- https://gchq.github.io/CyberChef/#recipe=ROT13(true,true,false,19)&input=d3BqdkpBTXtqaGx6aHlfazNqeTl3YTNrX2g0N2o2azY5fQ