# Descripción
Every file gets a flag. The SOC analyst saw one image been sent back and forth between two people. They decided to investigate and found out that there was more than what meets the eye [here](https://artifacts.picoctf.net/c/259/flag.png).
# Solución
Descargamos la imagen y apoyandonos de binwalk obtenemos la flag

- Primero descargamos la imagen, después usamos binwalk, con eso podemos ver que tiene archivos dentro de la imagen, por lo que usamos "binwalk -e" y con ello podemos obtener la imagen que contiene la flag 

picoCTF{Hiddinng_An_imag3_within_@n_ima9e_cda72af0}


# Notas adicionales
- 
# Referencias
- 