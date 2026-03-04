# Descripción
Alright, enough of using my own encryption. Flask session cookies should be plenty secure! http://wily-courier.picoctf.net:53055/
# Solución
Utilizar flask-unsign para conseguir la palabra secreta que se encuentra en la cookie, despues crear una cookie con esa firma para admin y con ello conseguir la bandera

- Primero es entrar a la página que se nos da, después acceder con "snickerdoodle" para poder obtener la cookie, luego con esta, utilizando el flask-unsign le vamos a pasar la lista de cookies, pues una de esta es la llave secreta, por lo que hacemos un ataque de fuerza bruta a la página para que nos de la palabra con la que fue firmada, luego con ella firmamos para obtener una cookie pero para el admin, con esto, obtenemos la cookie por lo que solamente es aplicar a la página un curl con la cookie conseguida junto con un grep pico para obtener la flag

picoCTF{cO0ki3s_yum_98b76c03}


# Notas adicionales
- 
# Referencias
- 