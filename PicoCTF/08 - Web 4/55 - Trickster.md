# Descripción
I found a web app that can help process images: PNG images only! Try it [here](http://atlas.picoctf.net:54340/)!
# Solución
Utilizar un webshell que pase el filtro, luego ejecutarlo desde el navegador y con ello ir navegando hasta conseguir la flag

- Primero es entrar a la página que se nos da, después creamos un archivo el cual tenga de nombre "webshell.png.php", en el escribimos PNG y el código para poder hacer una webshell luego lo subimos a la página, una vez pasa el filtro solamente en el link es añadirle "/uploads/webshell.png.php?cmd=cat ../GNTDOMBWGIZDE.txt", con ello obtenemos la flag

picoCTF{c3rt!fi3d_Xp3rt_tr1ckst3r_3f706222}


# Notas adicionales
- 
# Referencias
- 