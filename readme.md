Para implementar el proyecto con la encuesta, se debe realizar la instalacion de un servidor independiente de plataforma (Open Source), que consiste en la base de datos MySQL, servidor web Apache y los interpretes necesarios para lenguajes PHP y Perl, que posee el nombre de XAMPP. Una vez realizada la instalacion(Incluye la definion de nuestra Base de datos), iniciamos el paquete XAMPP, y nos dirigimos a nuestro navegador web, e introducimos la direccion Https://localhost endonde nos aparecerá la pagina por defecto de XAMPP , que nos arroja informacion acerca del servidor nativo que poseemos, datos de la conexion, etc. 

Desde este momento está preparado nuestro servidor para ser "montado" por nuestra aplicacion web. Posteriormente nos dirigimos a la direccion Https://www.limesurvey.org, y descargamos la aplicacion open source para la aplicación de encuestas en línea, escrita en PHP y que utiliza bases de datos MySQL, PostgreSQL o MSSQL. 

Una vez realizada la descarga, descomprimimos nuestro paquete con un programa determinado de compresion de archivos (preferencia WINRAR) en una carpeta definida, y nos dirigimos a la direccion donde instalamos previamente XAMPP (Generalmente C:\Xampp), ubicamos la carpeta HTDOCS en donde está contenido archivo index por defecto de XAMPP la cual borraremos o simplemente la reubicaremos en una carpeta. Una vez ahí, copiamos la carpeta previamente extraída y nos dirigimos nuevamente a nuestro navegador en donde volvemos a ingresar Https://Localhost, que seleccionaremos nuestra carpeta Limesurvey y procederemos posteriormente la instalacion de la aplicacion.



CREATE:

Proceso para crear una nueva encuesta

1.	Se debe abrir el navegador y la barra de direcciones colocar localhost/limesurvey/admin
2.	Luego ingresar usuario y clave
3.	Ir al icono “+” que se encuentra en la esquina superior derecha, y presionarlo.
4.	Acá se nos presenta las opciones: General, Presentación y navegación, Publicación y control de acceso, Notificación y manejo de datos, Participantes, Importar y finalmente copiar, estas son opciones del formato de la encuesta.
5.	Acá se crea el título de la encuesta, el mensaje de bienvenida y el mensaje de despedida, y algunas opciones de la encuesta como: URL de salida, descripción de la URL, formato de fecha, decimal mark, el administrador, el email del administrador, rebotes de correo, N° de fax. Luego de completar se presiona el botón guardar para proseguir.
6.	Luego aparecerán las características de la encuesta con el respectivo link para ir a la encuesta y contestarla, pero primero debemos agregar el grupo de preguntas.
7.	En la esquina superior derecha en la parte donde sale grupo de preguntas se selecciona el botón “+”, así para crear un grupo de preguntas, se le agrega título y la descripción y se presiona el botón guardar grupo de preguntas.
8.	Luego en la esquina superior derecha y debajo de grupo de preguntas, sale la opción preguntas y al lado de esta se encuentra el botón “+”, lo seleccionamos para agregar preguntas.
9.	A cada pregunta se le puede asignar un código, el nombre de la pregunta, ayuda, tipo de pregunta, al grupo de preguntas que pertenece, si es obligatoria, la relevancia y la validación. Finalmente le damos al botón agregar pregunta para poder agregar nuestra pregunta a la encuesta.
10.	El paso 8 y 9 se puede repetir las veces que sea necesario, ya que depende del usuario cuantos grupos de pregunta desea agregar y la cantidad de preguntas que se agregaran por grupo de pregunta.
11.	En la parte superior izquierda, en la segunda barra de menús en la parte que dice Encuesta “nombre de la encuesta”, en el icono del engranaje se puede ver una vista previa de la encuesta.
12.	En el mismo menú, el primer icono (cuadrado rojo), se presiona y sirve para activar la encuesta, salen unas condiciones y damos al botón save/ Activate survey, y nos aparecerá un mensaje de que el cuestionario ha sido activado, también nos sale la opción de restringir la encuesta, esto depende del usuario y damos al botón pertinente.
13.	Finalmente nos aparece la encuesta con sus características y sale la URL de la encuesta, ahí pinchamos al link y vamos a responder la encuesta.


DELETE:

Proceso para eliminar nueva encuesta
(Omitiremos los pasos de inicio de sesión previamente explicados, ya que se infiere que la encuesta será borrada dentro de la misma sesión)
1.	Estando en el menú del administrador, en la parte superior izquierda donde dice Encuesta “Nombre de la encuesta”, en el icono donde sale cruzado un desatornillador y un martillo, pinchamos y sale la opción eliminar encuesta.
2.	Nos saldrá un mensaje de advertencia de que se eliminara completamente y todo lo asociado a ella, damos en el botón eliminar encuesta. De esta manera se borra la encuesta y nos devuelve al menú principal del panel de administrador.
3.	Vamos a la parte superior derecha en el combo box donde salen “Encuestas:” y podemos verificar que la encuesta ha sido eliminada.
