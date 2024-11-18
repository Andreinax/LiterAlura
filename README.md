# LiterAlura
<p>Este proyecto es un buscador de libros, que utiliza la API de gutendex para realizar la consulta tanto del nombre del libro como del autor, el idioma disponible y la cantidad de descargas que ha tenido.</p>

### Caracteristicas  
- Tienes a tu disposición 73658 libros para consultar.
- los libros consultados quedan guardados en la base de datos para poder volver a ser consultados cuando quieras. 

### Uso 
1. La aplicación de divide en 4 segmentos
- Service
- Repository
- Principal
- Model

2. Nos situamos sobre el segmento de principal y damos clic sobre la clase Principal, acá encontramos la mayor parte del código como el menú y las funciones.

3. Para iniciar la aplicación nos dirigimos al segmento de service y damos clic sobre LiterAluraApplication y ahora volvemos a dar clic pero sobre la línea 11 y damos en “Run”.

4. Una vez cargada la aplicación nos mostrara el siguiente menú.

5. Al dar clic en la opción 1 nos solicitara que ingresemos el nombre del libro y después nos traerá la información del libro como título, autor, fecha de nacimiento, fecha de muerte, idioma y cantidad de descargas y lo guardara en la base de datos.

6. Al dar clic en la opción 2 nos mostrara los libros que hemos buscado y que se han guardado en la base de datos.

7. Al dar clic en la opción 3 nos muestra los libros guardados y nos pide ingresar el nombre del libro para darnos mas detalladamente los datos del autor.

8. Al dar clic en la opción 4 nos solicita fecha inicial y final para buscar un autor que este guardado en la base de datos y dependiendo nos trae la información y de no encontrar coincidencias con la fechas nos indicara que no encontró autores vivos entre esas fechas.


9. Al dar clic en la opción 5 nos mostrara un menú de unos determinados idiomas a escoger y nos indicara si hay libros con ese idioma disponibles.



