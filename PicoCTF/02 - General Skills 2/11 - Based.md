# Descripción
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337?
Connect with nc fickle-tempest.picoctf.net 55129.
# Solución
Conectarnos a la pagina y port indicados, después ir traduciendo poco a poco las diversas palabras que se nos entregan, primero un binario, después decimales y por último hexadecimal

- Usar una herramienta web como cyberchef
https://gchq.github.io/CyberChef/#recipe=From_Binary('Space',8)&input=MDExMDAwMTEgMDExMDExMTEgMDExMDExMDEgMDExMTAwMDAgMDExMTAxMDEgMDExMTAxMDAgMDExMDAxMDEgMDExMTAwMTA
https://gchq.github.io/CyberChef/#recipe=From_Octal('Space')&input=MTQxIDE1NiAxNTEgMTU1IDE0MSAxNjQgMTUxIDE1NyAxNTY
https://gchq.github.io/CyberChef/#recipe=From_Hex('None')&input=NjY2MTZjNjM2ZjZl

picoCTF{learning_about_converting_values_6c3Fb625}


# Notas adicionales
- Puede además utilizarse alguna distro de linux para hacerlo localmente
- Se puede utilizar un interprete de python para ir haciendo cada traducción
# Referencias
- https://gchg.github.io/CyberChef
- https://webshell.picoctf.org/