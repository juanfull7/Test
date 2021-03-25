Test
Custom Theme WP Bootstrap

Especificaciones del proyecto: 

Objetivo
Construir un template de blog para wordpress a partir de una plantilla personalizada

Plantilla:
la plantilla que se utilizo para el desarrollode este proyecto es WP Bootstrap Starter https://es-co.wordpress.org/themes/wp-bootstrap-starter/ , la plantilla tiene las ventajas de que trae integrada el framework de estilos css de Bootstrap de manera que se ahorro el trabajo de hacer la importacion de los scripts y los archivos del mismo framework

Plugins:
el plugin utilizado como soporte de contenido al proyecto es FakerPress https://es.wordpress.org/plugins/fakerpress/, la utilidad del plugin es crear contenido ficticio para los posts del blog , usuarios, etc...

Maquetacion:
para la maquetacion del template del blog se utilizo el PHP del core de wordpress y HTML basado en el diseño del siguiente blog https://getbootstrap.com/docs/5.0/examples/blog/

Configuracion del header:
el header es el mismo para todo el sitio, de manera que se puede cambiar el color de fondo, el banner title y el banner tagline  desde Appearance -- Customize -- Header Banner ![image](https://user-images.githubusercontent.com/38046686/112413117-a4813100-8ced-11eb-87d9-77f37849991b.png)

si se deja en blanco estos titulos , el banner por defecto tomara como titulo el nombre del post o page !!

Instalacion de la plantilla en local host:

Paso 1
 en este ejemplo se utilizo el Xampp como hosting local, antes que nada debemos entender de que la instalacion del wordpress desde el localhost se debe hacer desde los modulos de bitnami ![image](https://user-images.githubusercontent.com/38046686/112415114-3e96a880-8cf1-11eb-845a-dfb1b3f71109.png)
pero en este ejemplo no sera necesario

Paso 2
por lo general despues de instalar el wordpress, este quedara dentro de una carpeta llamada apps esta es la ruta C:\xampp\apps en esta carpeta es donde vamos a descomprimir el archivo wordpresstest.zip

Paso 3
luego debemos ingresar a el phpmyadmin de xammp http://localhost:8080/phpmyadmin/index.php aqui debemos importar la base de datos anexa dentro del archivo comprimido  llamada bitnami_wordpress.sql despues de haber hecho esto ya tenemos lista nuestra base de datos

Paso 4
despues de descomprimir el archivo del wordpress  en el localhost debemos de ingresar al dashboard del administrador del wordpress desde el navegador por lo general se ingresa con la siguiente url http://localhost:8080/wordpress/wp-admin aqui ingresaremos el usuario y la contraseña user:admin ; pass:admin 

Paso 5
despues de ingresar al dashboard debemos activar la plantilla esto lo hacemos desde Appearance -- Themes, con esto la plantilla quedara activada y lista para su uso...
