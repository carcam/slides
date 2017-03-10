## Optimizando el entorno 
* Usar un servidor con PHP7
* Servidor con sistemas de caché de PHP como Memcache o Memcached
* Usar un fichero .htaccess optimizado:
	* Tiempos de expiración
	* Activar mod_deflate (compresión gzip)

Note:
* No hay excusas para no usar PHP7. Si tu servidor no lo soporta ¡Huye!
* Las cachés liberan al servidor de tareas repetitivas. Memcache hace precisamente eso.
* Los tiempos de expiración tienen que ser adecuados a cada tipo de fichero 

