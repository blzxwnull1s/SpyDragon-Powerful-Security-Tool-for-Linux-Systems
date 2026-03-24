# SpyDragon-Powerful-Security-Tool-for-Linux-Systems
v.20 tool
SpyDragon v.2 es una herramienta de inteligencia de código abierto orientada a ciberseguridad que funciona completamente desde la terminal en sistemas Linux. Su objetivo es proporcionar múltiples funcionalidades de análisis, reconocimiento y obtención de información en un solo entorno interactivo, permitiendo al usuario ejecutar tareas OSINT, análisis de red y recopilación de datos de forma rápida y eficiente. Esta herramienta está diseñada para uso educativo, auditorías autorizadas y pruebas de seguridad controladas. El uso indebido o sin permiso puede ser ilegal y es responsabilidad del usuario.

Para comenzar a utilizar SpyDragon no es necesario realizar procesos complejos de instalación. El programa está diseñado para ejecutarse directamente desde la terminal mediante un método simple de copiar y pegar. Primero debes asegurarte de tener un entorno Linux funcional con Python3 instalado, así como conexión a internet para que las funciones OSINT puedan consultar servicios externos. Una vez cumplido esto, copia el código del programa SpyDragon y pégalo en un archivo dentro de tu sistema, por ejemplo con el nombre spydragon.py. Luego abre una terminal en el directorio donde guardaste el archivo y ejecuta el comando python3 spydragon.py. También puedes asignar permisos de ejecución con chmod +x spydragon.py y ejecutarlo directamente si el script lo permite.

Al iniciar, SpyDragon mostrará una interfaz en la terminal con un banner y un menú numerado que contiene todas las funcionalidades disponibles. El usuario interactúa escribiendo el número correspondiente a la opción deseada y presionando Enter. Cada módulo está diseñado para ejecutarse de forma independiente y solicitará los datos necesarios según la función seleccionada.

Las opciones relacionadas con direcciones IP permiten obtener información detallada sobre una IP específica, incluyendo datos de geolocalización, proveedor de servicios y posibles indicadores de uso de VPN o proxy. También es posible consultar reputación de IP, verificar si se encuentra en listas negras y realizar análisis WHOIS para conocer detalles del registro.

Las funciones de red incluyen herramientas clásicas como ping para verificar conectividad, traceroute para analizar rutas de red, escaneo de puertos abiertos y análisis de puertos específicos. También permite obtener información de la red local, identificar dispositivos conectados y realizar escaneos básicos dentro de la misma red.

En el apartado de dominios y web, SpyDragon ofrece consultas WHOIS de dominios, resolución DNS, obtención de cabeceras HTTP, detección de tecnologías web utilizadas por un sitio, análisis SSL/TLS y enumeración de subdominios mediante técnicas OSINT. También incluye herramientas para analizar archivos robots.txt y realizar búsquedas básicas mediante Google Dorks.

Las funciones OSINT orientadas a personas y cuentas permiten buscar nombres de usuario en múltiples plataformas utilizando herramientas como Sherlock, analizar correos electrónicos, revisar si un email ha aparecido en filtraciones de datos, analizar cabeceras de correos y obtener información relacionada con números telefónicos, incluyendo operadora y geolocalización aproximada.

SpyDragon también incluye utilidades para análisis de archivos, como cálculo de hashes y extracción de metadatos EXIF de imágenes, lo cual puede ser útil en investigaciones digitales. Asimismo, permite consultar nodos de salida de la red Tor, buscar información en bases de datos públicas como Shodan y Pastebin, y realizar análisis generales de URLs.

El sistema incluye una opción para generar reportes con la información recopilada durante el uso, facilitando la documentación de análisis. También dispone de una sección de ayuda y aviso legal que recuerda al usuario la importancia del uso ético y autorizado de la herramienta.

Para salir del programa, simplemente se debe seleccionar la opción correspondiente en el menú principal. En caso de errores durante la ejecución, es recomendable verificar la conexión a internet, dependencias necesarias y permisos del sistema.

SpyDragon está pensado como una herramienta ligera, flexible y fácil de usar, ideal para investigadores, estudiantes de ciberseguridad y profesionales que necesiten un conjunto de utilidades OSINT accesible desde la terminal sin configuraciones complejas.
