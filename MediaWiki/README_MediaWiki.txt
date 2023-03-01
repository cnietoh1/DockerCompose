Instrucciones de despliegue MediaWiki
Crear el fichero docker-compose.yml en el directorio donde se va a desplegar el servicio.
Asegurarse que los contenedores se crearon correctamente y están en funcionamiento, si no es así se podrán iniciar manualmente desde la aplicación de Docker o con el comando docker-compose start.
Ejecutar el comando 'docker-compose up -d' dentro del directorio donde se encuentra el fichero 'docker-compose.yml' para montar la configuración del sitio.
Acceder a la url del servicio web, en este caso localhost:8081 ya que es el puerto asignado en el fichero yml.
En este punto el servicio esta activo pero el fichero LocalSettings no lo encuentra, hhe seguido todos los pasos de la guía y comprobando todo pero no he conseguido hayar el problema. Por todo lo demas esta perfecto.