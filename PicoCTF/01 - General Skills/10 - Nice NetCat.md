# Descripción
There is a nice program that you can talk to by using this command in a shell: nc wily-courier.picoctf.net 53396, but it doesn't speak English...
# Solución
Conectarnos a la pagina y port indicados, después traducir el código dado

- Usar una herramienta web como cyberchef
https://gchq.github.io/CyberChef/#recipe=From_Decimal('Space',false)&input=MTEyIDEwNSA5OSAxMTEgNjcgODQgNzAgMTIzIDEwMyA0OCA0OCAxMDAgOTUgMTA3IDQ5IDExNiAxMTYgMTIxIDMzIDk1IDExMCA0OSA5OSA1MSA5NSAxMDcgNDkgMTE2IDExNiAxMjEgMzMgOTUgNDkgNTcgNTMgMTAyIDEwMSAxMjUgMTA

picoCTF{g00d_k1tty!_n1c3_k1tty!_195fe}


# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
- Se puede utilizar un interprete de python para hacer la traducción
# Referencias
- https://gchg.github.io/CyberChef