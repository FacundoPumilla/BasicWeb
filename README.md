## Web basica
_
#### utilzar con docker-compose
_
- Bajar el zip.
- Situarse un nivel antes del directorio a crear
- Descomprimir
~~~
unzip -q BasicWeb-master.zip -d **directorioACrear**
~~~
- Borrar el archivo zip (si gusta)
~~~
rm BasicWeb-master.zip (o nombre del zip)
~~~
- Modificar el archivo .env
- Modificar el archivo host en el equipo
- Modificar solo el interior de la carpeta **web**

#### Comandos docker
~~~
docker-compose up
~~~
<sub>Permite iniciar el archivo docker.compose.yml y dejar en modo debug.</sub>
~~~
docker-compose up -d
~~~
<sub>Permite iniciar el archivo docker.compose.yml y liberar la consola.</sub>
~~~
docker-compose stop
~~~
<sub>Detiene el demonio docker y todos sus imagenes en ejecucion.</sub>
