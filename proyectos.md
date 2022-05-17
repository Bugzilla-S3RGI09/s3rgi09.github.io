[Home](index.md) | [Repositorios](repositorios) | [Proyectos](proyectos) | [Contacto](contacto)

# Proyectos
## La web de los proyectos:
Web de proyectos [H4ckS0r7](https://h4cks0r7.github.io/)

## Mi GitHub 
donde estan todas las herramientas [GitHub](https://github.com/S3RGI09?tab=repositories)

# Manual de Pegasus
Estoy seguro de que has escuchado hablar del poderoso spyware Pegasus de la empresa de ciberseguridad israelita NSO group, no me digas que nunca has deseado comprarlo, aunque sea para tenerlo de adorno, el caso es que por su desorbitado precio de 6.000.000$ nos conformamos con su manual de 15$, pero y si te digo que puedes conseguir su manual completamente gratis. Antes de empezar tengo que agradecer a [S4vitar (Marcelo Vazquez)](https://s4vitar.github.io/) por dejar a toda la comunidad acceder a un pdf con el manual de Pegasus.
![Captura de pantalla_2022-05-17_21-26-05](https://user-images.githubusercontent.com/96842235/168900959-304c6f8f-0507-45b9-a947-185a0e2b406d.png)
![Captura de pantalla_2022-05-17_21-27-50 (1)](https://user-images.githubusercontent.com/96842235/168901306-f36bdaaf-b5f9-4172-a8d0-c1bbcf6d45a0.png)
### Link del pdf
[Link para el manual de Pegasus](https://ia801005.us.archive.org/1/items/nso-pegasus/NSO-Pegasus.pdf)

# Manual de instrucciones de Scan
![Añadir un subtítulo](https://user-images.githubusercontent.com/96842235/167315668-5b6290ae-3acd-451e-abb4-10b2fd353a23.png)

Herramienta para escanear puertos de una IP. El script escrito en python funciona gracias a la libreria "Python-nmap" que puede ver en la web Indices de Paquetes de Python (PyPI) e instalar con pip, lo comodo de esto es que no es necesario hacer todo esto, ya que el repositorio tiene un pequeño script llamado "instalacion.sh" para automatizar todas estas tareas y darle permisos de ejecucion al script.

---------------------------------------------------------------------------------------------------------------------------------------------------------

# Como hacer un escaneo
Hacer un escaneo con Nmap puede llegar a ser algo dificil para la gente que recien a empezado en la informatica por culpa de todos sus parametros, yo lo que recomiendo es que si estas aprendiendo NO UTILICES ESTE SCRIPT, ya que lo unico que aprenderias sera a tenerlo todo echo. Pero si eres un profesional o un aficionado con conceptos avanzados sobre Nmap y su sondeo, este script solo te hara ahorrar tiempo. Para iniciar un escaneo es muy simple, solo vete al directorio donde tienes el archivo del script y haz en tu consola "./scan.py" si le has asignado permisos de ejecucion, si no tendras que hacer un "python scan.py", de las dos maneras tendras el script corriendo, ahora solo pon la IP a la que quieres hacer el escaneo, en unos 2-3 segundos tendras los resultados del escaneo en tu pantalla.
![Captura de pantalla_2022-05-08_22-04-01](https://user-images.githubusercontent.com/96842235/167313797-12f5d574-fc3d-4f9b-85e2-3de28296440d.png)

---------------------------------------------------------------------------------------------------------------------------------------------------------

# No funciona el escaneo
Si el escaneo no funciona, asegurate de que tienes el paquete Python-nmap instalado, si no lo tienes haz un "pip install python-nmap".
Si aun asi no funciona y te sale un error de sintaxis o de nombre, copia el codigo de Scan desde GitHub a tu script de Scan, esto puede ser porque alguien o tu ha tocado el codigo de Scan y a puesto algo que bloquee otra cosa.
Si sigue sin funcionar y su pc o laptop tiene un hardware muy antiguo instale ScanLite, tambien en mi GitHub.

---------------------------------------------------------------------------------------------------------------------------------------------------------

# Como instalar Scan
Para instalar el script es muy simple y hay dos opciones. La primera y la más facil es ejecutar en tu terminal "bash instalacion.sh", este archvio es un pequeño script que sirve para realizar todas las tareas para utilizar correctamente Scan sin errores. Y la segunda es seguir un pequeño resumen de la instalacion que haremos aqui:

[Paso 1:] Vamos a empezar por lo basico, instalaremos la libreria Python-nmap, ponga en su consola: pip install python-nmap

[Paso 2:] Ahora hay que dar permisos de ejecucion al script y a todo lo necesario, ponga en su terminal los siguientes comandos, solo funciona en sistemas tipo UNIX-LIKE: chmod +x ./scan.py ./scan1.0.py RecoverScanScript.sh

[Paso 3:] Ya hemos acabado, ahora puede borrar el archivo instalacion.sh si quiere, ahora a hackear y a pasarlo bien.

---------------------------------------------------------------------------------------------------------------------------------------------------------

# Scan:Version 1.0
En este repositorio viene incluido la primera version del script Scan, esta version esta hay para que vea el avance, las mejoras y el contrastre desde la primera version a la ultima. No tiene nada util en el fondo ya que es mas lento que la ultima version y mas simple.
![Screenshot_2022-05-08_22_06_50](https://user-images.githubusercontent.com/96842235/167313912-a427bd67-7291-485b-89b2-b244dcc247f3.png)

---------------------------------------------------------------------------------------------------------------------------------------------------------

# RecoverScanScript
Este script creado en Bash sirve para recuperar el script Scan. Es una herramienta de recuperacion para solucionar errores por si a pasado algo en el paquete Python-nmap, como que no se a descargado correctamente. Este script borra todos los datos de la carpeta Scan y todos sus archivos dentro de la carpeta al igual que el paquete python nmap y reinstala el repositorio de github. Una vez instalado el repositorio, ejecuta el instalador de Scan, y se instala el paquete Python-nmap, se le da permisos de ejecucion a todos los archivos y se borra a si mismo para tener todo como el primer dia. esta herramienta esta pensada para resolver errores graves como un problema al instalar el repositorio o el paquete Python-nmap.

---------------------------------------------------------------------------------------------------------------------------------------------------------

# Fin
Le doy gracias a todo el mundo que a instalado Scan, a mi me alegra saber que estoy contribuyendo en ayudar a otras personas que comparten la misma pasion por la informatica que yo, la verdad, si yo hubiese tenido este script cuando habia aprendido medianamente nmap, me las habria gozado, literalmente podria estar ahora mismo en la carcel por haber hackeado la red wifi de el centro comercial de mi ciudad (Nunca lo e echo, NUNCA) espero que os halla servido esta informacion y sobre todo el script.




# Manual de instrucciones de tssrecon
Script creado en Bash para automatizar la fase de reconocimiento.

---------------------------------------------------------------------------------------------------------------------------------------------------------

Para ponerlo en marcha hay que seguir estos pasos:
$ cd tssrecon
$ ./tssrecon.sh (introducir la IP objetivo)

---------------------------------------------------------------------------------------------------------------------------------------------------------

Cabe aclarar que aunque el script utilice otro script tambien programado por mi, no es necesario tenerlo instalado, ya que cuando clona el repositorio tambien se instala y se compila el script scan.py.

![Captura de pantalla_2022-05-11_23-24-36](https://user-images.githubusercontent.com/96842235/167950278-05fd70cd-c0a4-4b6a-b017-c0f56bd31c7c.png)
