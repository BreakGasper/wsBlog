# RESTBlogdeInternet
WebServices de Blog de internet 
--Crear una Base de datos
Create database Blog_database;
--Crear la tabla donde se alamcenara la informacion
CREATE TABLE BlogProps(id_blog int NOT NULL PRIMARY KEY AUTO_INCREMENT, titulo TEXT, autor text, fecha_publicacion Date, contenido TEXT);
--Montar servidor
--instalar Xampp
--en la carpeta htdocs copiar la carpeta wsBlog
--abrir el ejecutador Xampp - control y presionar start MYSQL
--presionar en ambos al boton admin
--en el caso de MYSQL crea la base de datos y la tabla que estan al inicio de readme
-------------------------------------------------------------------------------------------
--ANDROID STUDIO
--en android studio solo hay que cambiar el archivo GlobalConfig.kt
-- var ws_url = "http://192.168.1.78/wsBlog/"  --Se usa de manera local solamente tienes ir
-- a Simbolo Sistema y teclear ipconfig y cambiar unicamente la ip de este ejemplo por la tuya
-- var ws_url = "https://monsheep.000webhostapp.com/wsBlog/"  --Son los servicios que yo monte
-- en 000webhostapp utilizando un dominio asi esta actualmente configurado el apk


