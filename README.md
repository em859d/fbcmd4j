El producto final será un cliente de Facebook en línea de comando (FBcmd4j) que cuente con
las siguientes funcionalidades:
- Obtener el NewsFeed del usuario que ejecuta la aplicación con la posibilidad de
guardar las últimas N publicaciones en un archivo de texto.
- Obtener el Wall del usuario que ejecuta la aplicación con la posibilidad de guardar las
últimas N publicaciones en un archivo de texto.
- Publicar un estado en el Wall del usuario que ejecuta la aplicación.
- Publicar un Link en el Wall del usuario que ejecuta la aplicación.
En tanto a la configuración de la aplicación:
a. Un archivo que contenga los parámetros mínimos para conectarse a Facebook
(Tokens, permisos), por ejemplo, fbcmd4j.properties
b. La configuración se podrá hacer por medio del mismo cliente o edición directa del
archivo especificado.
Puntos adicionales:
- La aplicación contará con un log llamado fbcmd4j.log donde se registrarán las
actividades de la aplicación en sus diferentes niveles. 
- La aplicación será totalmente portable, es decir, que se podrá ejecutar en cualquier
sistema operativo que tenga instalado Java8.
- La aplicación contará con las dependencias incluidas que con solo ejecutarla, se
podrá ejecutar sin necesidad de descargar librerías adicionales.
- La aplicación contará con el manejo correcto de recursos y excepciones, es decir, si
ocurre una excepción el programa no saldrá sino que seguirá ejecutándose y mostrará
el mensaje de error en la pantalla.
