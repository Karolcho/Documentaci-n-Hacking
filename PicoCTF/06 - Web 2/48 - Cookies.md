# Descripción
Who doesn't love cookies? Try to figure out the best one. http://wily-courier.picoctf.net:59130/
# Solución
Entrar a la terminal y utilizando un ciclo que llegue de 0 a 20 usando un curl -s con el link dado hasta conseguir la flag

- Entregar a la terminal y usando el siguiente comando "for i in {0..20}; do curl -s http://wily-courier.picoctf.net:59130/check -H "Cookie: name=$i"; done | grep picoCTF", para con ello conseguir la flag


picoCTF{3v3ry1_l0v3s_c00k135_a4dadb49}


# Notas adicionales
- 
# Referencias
- http://wily-courier.picoctf.net:59130/