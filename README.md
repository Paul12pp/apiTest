# apiTest
Api for Hit technical test

# Intrucciones de instalación 
1. Crear la base de datos con el nombre especificado en el .env
2. Correr las migraciones
3. Correr el servidor en el puerto de preferencia
4. Crear usuario para probar
5. O usar metodo para invitado

# El algoritmo
Consiste en la creacion de un código random de 6 digitos que se almacena en la base de datos y una funcion que al dar acceder al enlace corto redirige al enlace largo.
La URL BASE mas el codigo forma la url corta.
Ejemplo: 	http://127.0.0.1:8000/g0QGy8
URL BASE: 	http://127.0.0.1:8000
Código: g0QGy8

Cada vez que se accede a una url se cuenta la visita y se almacenan los datos de la visita en la tabla 'info_access'
