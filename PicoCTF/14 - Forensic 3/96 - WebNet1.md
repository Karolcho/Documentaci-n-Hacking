# Descripción
We found this [packet capture](https://challenge-files.picoctf.net/c_fickle_tempest/d1e9add4e31989553f239ebf71ba5972f9bed7bd4932f931e14bfba80d75f815/capture.pcap) and [key](https://challenge-files.picoctf.net/c_fickle_tempest/d1e9add4e31989553f239ebf71ba5972f9bed7bd4932f931e14bfba80d75f815/picopico.key). Recover the flag.
# Solución
Descargar el .pcap y usar la key que se nos da para el encriptado TLS para con ello poder conseguir la flag

- Primero debemos descargar el .pcap y la key, después debemos de usar Wireshark, con el le introducimos que maneje para el flujo de las TLS la key que se nos dio, para que con ello podamos desencriptar la información, luego de eso descargamos la imagen de vulture que tiene, y a la imagen le aplicamos un strings para poder obtener la flag

picoCTF{honey.roasted.peanuts}

# Notas adicionales
- 
# Referencias
- 