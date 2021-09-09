# rest_prueba_tecnica
rest api para prueba tecnica

intalacion 

ir a la carpeta del proyecto rest_prueba_ tecnica en cmd 
ejecutar mvn clean install
en la carpeta llamada target se encuentra el archivo generado 
prueba_tecnica-0.0.1-SNAPSHOT.jar

ejecutar ese archivo desde simbolo del sistemas
y queda corriendo el servidor en el puerto 4000

http://localhost:4000/services/personas

http://localhost:4000/services/personas/2

http://localhost:4000/services/personasTop3/3

http://localhost:4000/services/planetas

http://localhost:4000/services/planetas/2

http://localhost:4000/services/planetasTop3/3

si el puerto esta ocupado debe cambiar el puerto dentro del jar en la siguiente ruta

\prueba_tecnica-0.0.1-SNAPSHOT.jar\BOOT-INF\classes\application.properties

documentacion sobre los servicio en la siguiente url 

http://localhost:4000/services/swagger-ui.html#/servicios-controller





