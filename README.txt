-Autor de la Aplicacion Efim Ciubuc.

-Sobre el Proyecto:
	-Lenguajes de Programación: PHP;
	-Lenguaje de marcas: Html5;
	-lenguaje de diseño gráfico: CSS3;

-Mi visión en este ejercicio ha sido crear otra pagína de inicio donde el usuario pueda acceder a las dos partes Back-end y Front-end. Eso me ayuda estructurar mi aplicación.

-FRONT-END: Formulario de usuario (formulario.php ...)
	Aplicacion dividida en 2 partes Front-end & Back-end.
	Datos recopilados: Apellidos,Nombre,Fecha de nacimiento,Ciudad de nacimiento,Sexo,
	Aficiones { Deporte | Teatro | Cine | Bares },Foto.

-BACK-END: Formulario del administrador (admin.php ...)
	Visualiza datos de todos los usuarios { Apellidos + Nombre + ... los que se quieran mostrar... }
	Selecciona uno de ellos mostrando todos sus datos y permitiendo borrarlo.
	Permite añadir nuevos usuarios.


-Al guardar el fichero con datos he decidido elegir registros con la longitud variable:
	-me interesa guardar la integridad de los datos sin truncar los datos.
	-prefiero usar  un delimitador de cada registo '/'.
	-cada registro al escribir le añado un salto de linía de esta manera me aseguro que en una linía puede haber un solo registro.
	- no uso un indice para aceder a cualquier registo - simplemente recorro el archivo entero.

-Complementos:
	-He usado unos iconos de fuente gratuitas de FontAwesone.
	-He integrado la carpeta del recurso en el proyecto.   