# dockerRenderI-SA-Group

Ejecutar en una cmd el comando:

docker run -p {PUERTO}:80 -v {PATH_CARPETA}:/opt/app/src/frontend/index isagroup/governify-render

Donde: 
	- {PUERTO} es el puerto en el que se desea desplegar la aplicacion
	- {PATH_CARPETA} es el path absoluto de la carpeta DockerRender

Para abrir la aplicación, introducir en un buscador:

http://localhost:{PUERTO}/render?model=/index/model.json&view=/index/view.html&ctrl=/index/controller.js

o simplemente: http://localhost:{PUERTO}

e introducir como nombre de usuario y contraseña: isa
