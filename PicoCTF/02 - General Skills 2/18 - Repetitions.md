# Descripción
Can you make sense of this file? Download the file [here](https://artifacts.picoctf.net/c/471/enc_flag).
# Solución
Descargar el archivo indicado, después de ello aplicarle un cat, el texto codificado irlo decodificando poco a poco hasta obtener la flag

- Usar una herramienta web como cyberchef, después ir decodificando y repitiendo una y otra vez hasta conseguir la flag
https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=Y0dsamIwTlVSbnRpWVhObE5qUmZiak56ZEROa1gyUnBZekJrSVc0NFgyUXdkMjVzTURSa00yUmZPV0kxT1dJek5XTjlDZz09

picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_9b59b35c}


# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
- Se puede utilizar un interprete de python para hacer la traducción, dentro de un ciclo que lo repita hasta que consiga el flag
# Referencias
- https://gchg.github.io/CyberChef
- https://webshell.picoctf.org/