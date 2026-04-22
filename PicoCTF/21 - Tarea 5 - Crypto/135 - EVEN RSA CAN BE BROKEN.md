# Descripción
This service provides you an encrypted flag. Can you decrypt it with just N & e? Connect to the program with netcat: `$ nc verbal-sleep.picoctf.net 64080` The program's source code can be downloaded [here](https://challenge-files.picoctf.net/c_verbal_sleep/b1999e70e98a4fb11d441bd4ef60a948c1ae4a27a3a7154ed2678990b91f52e4/encrypt.py).
# Solución
Volver a apoyarnos de FactorBD para poder romper el RSA y obtener la flag

- Primero entramos a la página que se nos indica para obtener los datos, después usando de nuevo FactorBD podemos simplemente conseguir los números primos y con ello ir haciendo los cálculos hasta obtener la flag

picoCTF{tw0_1$_pr!m305af7255}


# Notas adicionales
- 
# Referencias
- https://colab.research.google.com/drive/1n4xYGXAxYwdHeQ6lcaWSqB7A2wnLp2at?usp=sharing