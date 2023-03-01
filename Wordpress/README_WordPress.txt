Instrucciones de despliegue WordPress
Crear el fichero docker-compose.yml en el directorio donde se va a desplegar el servicio.
Asegurarse que los contenedores se crearon correctamente y están en funcionamiento, si no es así se podrán iniciar manualmente desde la aplicación de Docker o con el comando docker-compose start.
Ejecutar el comando 'docker-compose up -d' dentro del directorio donde se encuentra el fichero 'docker-compose.yml' para montar la configuración del sitio.
Acceder a la url del servicio web, en este caso localhost:8083 ya que es el puerto asignado en el fichero yml.
Una vez dentro seleccionamos idioma, accedemos con las credenciales establecidas en el fichero yml.