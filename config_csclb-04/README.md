# Servidor del CSC Luis Buñuel

Este equipo se utiliza como servidor de arranque por red (dhcp y tftp) y como repositorio debian (en estos momentos solo 32 bits por falta e espacio en disco).
Tiene dos IPs porque la segunda (192.168.0.254) la asociamos al servicio de repositorio debian. De esta forma se pueden independizar los roles de arranque y repo sin cambios en los clientes. 
Hay un archivo con la lista de paquetes instalados (dpkg get-selections), otro con el enlace simbólico para la imagen de arranque por tftp y el directorio etc con la configuración.
