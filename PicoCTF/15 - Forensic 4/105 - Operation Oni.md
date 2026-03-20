# Descripción
Download this disk image, find the key and log into the remote machine. Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download disk image](https://artifacts.picoctf.net/c/70/disk.img.gz)
- Remote machine: `ssh -i key_file -p 63981 ctf-player@saturn.picoctf.net`
# Solución
Primero descargamos el archivo, obtenemos la key de ssh y después con ello entramos a la página para obtener la flag

- Primero descargamos el archivo que se nos da y lo descomprimimos, luego analizandolo podemos ver que contiene una llave ssh, por lo que la copiamos con "icat -o 206848 disk.img 2345 > id_ed25519", después nos damos permisos con esa misma llave con "chmod 600 id_ed25519" y luego de ello entramos a la página y cambiamos el apartado de key_file con nuestra nueva llave, entramos y aplicamos un "cat flag.txt" y con ello obtenemos la flag

picoCTF{k3y_5l3u7h_b5066e83}


# Notas adicionales
- 
# Referencias
- 