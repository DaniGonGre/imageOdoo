### Entorno de Desarrollo Odoo

Para crear el entorno de desarrollo odoo con python: 
1. Creamos un proyecto en PyCharm que contenga un archivo llamado: *docker-compose.yml*
2. Configuramos el docker.compose para que contenga la imagen de odoo y la base de datos postgres.
3. Iniciamos el documento con el siguiente comando: ```docker-compose up```
4. Conectamos el proyecto con la base de datos:
   1. Database
   2. (+)Data Source
   3. PostgreSQL
5. Hacemos un test de conexión con la base de datos para ver si funciona.
![Captura desde 2023-02-28 10-37-36.png](..%2F..%2FIm%C3%A1genes%2FCapturas%20de%20pantalla%2FCaptura%20desde%202023-02-28%2010-37-36.png)
6. Entramos en localhost:8069 (o el puerto que hayamos indicado) en el navegador y nos pedirá los datos de la base de datos, 
un ejemplo de como completarlo (si la base de datos ya está en uso deberemos cambiarle el nombre):
![Captura desde 2023-02-28 10-20-15.png](..%2F..%2FIm%C3%A1genes%2FCapturas%20de%20pantalla%2FCaptura%20desde%202023-02-28%2010-20-15.png)