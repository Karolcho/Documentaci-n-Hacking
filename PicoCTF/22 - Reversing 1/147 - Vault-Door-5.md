# Descripción
In the last challenge, you mastered octal (base 8), decimal (base 10), and hexadecimal (base 16) numbers, but this vault door uses a different change of base as well as URL encoding! The source code for this vault is here: [VaultDoor5.java](https://challenge-files.picoctf.net/c_fickle_tempest/a8fa4d19d7d2445ee8152987624b46c1ff4eeeab9319ab48c513f66f5b903ef8/VaultDoor5.java)
# Solución
Descargar el archivo y conseguir la flag

- Primero descargamos el archivo que se nos da, después podemos ver que la flag esta encriptada con Base64 y con URL, por lo que podemos apoyarnos de cyberchef para conseguir la flag

picoCTF{c0nv3rt1ng_fr0m_ba5e_64_7f855fc5}


# Notas adicionales
- 
# Referencias
- https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)URL_Decode(true)&input=IkpUWXpKVE13SlRabEpUYzJKVE16SlRjeUpUYzBKVE14SlRabEpUWTNKVFZtIiAgICAgICAgICAgICAgICAgICAgICAgICJKVFkySlRjeUpUTXdKVFprSlRWbUpUWXlKVFl4SlRNMUpUWTFKVFZtSlRNMiIKIkpUTTBKVFZtSlRNM0pUWTJKVE00SlRNMUpUTTFKVFkySlRZekpUTTEi