# Descripción
In RSA, a small e value can be problematic, but what about N? Can you decrypt this? [values](https://challenge-files.picoctf.net/c_wily_courier/748a8bfc7244df64f48a6ad1d79b5900ee905dd28ebbcd5856652b0e4435393f/values)
# Solución
Utilizar un ataque del módulo débil para conseguir la flag

- Primero descargamos el archivo que se nos da para poder conseguir los valores, después se puede observar que N es un número muy pequeño por lo que aprovechándonos de esto podemos obtener los valores de p y q para obtener la llave privada, después hacemos un código el cual se comunique con FactorDB para poder obtener de una manera simple la flag y al ejecutarlo nos la da

picoCTF{sma11_N_n0_g0od_1dc7ae91}


# Notas adicionales
- 
# Referencias
- https://colab.research.google.com/drive/1hVsnMgOJ4k2bQAcYZ-KdiAz3r68Xc262?usp=sharing