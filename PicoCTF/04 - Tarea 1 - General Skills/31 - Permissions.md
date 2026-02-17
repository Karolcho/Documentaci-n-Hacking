# Descripción
Can you read files in the root file? The system admin has provisioned an account for you on the main server: `ssh -p 59038 picoplayer@saturn.picoctf.net` Password: `33qE7mB5BF` Can you login and read the root file?
# Solución
Usando ssh conectarnos a la pagina con el usuario y contraseña indicados y obtener la flag

- Utilizar el webshell integrado, después acceder a la página que se nos da y aplicar un "ls -la", luego dar un "cd ..", y aplicar un "sudo vi /root/.flag.txt" y con ello obtenemos la flag

picoCTF{uS1ng_v1m_3dit0r_3dd6dcf4}

# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
# Referencias
- https://webshell.picoctf.org/