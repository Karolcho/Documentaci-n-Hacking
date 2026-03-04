# Descripción
The flag is somewhere on this web application not necessarily on the website. Find it. Check [this](http://saturn.picoctf.net:56217/) out.
# Solución
Entrar a la página dada, después acceder al robots.txt con ello descifrar la página donde se encuentra nuestra flag y obtener la flag

- Primero es entrar a la página, después se entra a robots.txt, allí se encuentra un texto codificado en base64, lo decodificamos y son 3 partes, nos quedamos con la segunda que es el link que necesitamos y con ello obtenemos la flag al introducirlo en el URL

picoCTF{Who_D03sN7_L1k5_90B0T5_718c9043}

# Notas adicionales
- Se puede utilizar el CyberChef para conseguir la decodificación del código
# Referencias
- https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=YW5NdmJYbG1hV3hsTG5SNGRBPT0K&oeol=VT