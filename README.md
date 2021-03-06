# Sistema de Adopci贸n de Mascotas Rescatadas: 
<p align="center"><img src="https://github.com/LordZapallo/Adopcion-Mascotas/blob/main/public/imagenes/avt.png" width="400"></p>
</b>

## Video de Evidencia de Funcionamiento
[![Link youtube.com](https://img.youtube.com/vi/T8K2GCosSNQ/hqdefault.jpg)](https://youtu.be/T8K2GCosSNQ "Link youtube.com")

## Sobre el Proyecto 馃殌
Aplicaci贸n Web con el objetivo de facilitar a cualquier persona el proceso de adopci贸n de Mascotas rescatadas que viven Albergues, la aplicaci贸n gestiona todos los aspectos del proceso v铆a online, siendo el 煤nico paso presencial pasando el proceso exitosamente el acudir al albergue a retirar su mascota adoptada.

## Autor 馃搵
Autor: Michael Andr茅s G贸mez N煤帽ez.  <br>   Universidad: Universidad T茅cnoca Particular de Loja

### Pre-requisitos 馃搵
Servidor de Base de Datos My-SQL. como: XAMPP, WAMPP, etc. 
Recomendacion de Descarga: <a href="https://www.apachefriends.org/es/download.html">XAMPP</a><br> 
Instalado Node.js 
Descarga: <a href="https://nodejs.org/es/download/">Node.js</a><br> 
Instalado Composer 
Descarga: <a href="https://getcomposer.org/download/">Composer</a>
## Instalaci贸n 馃敡
1. Descargar Repositorio:
```
git clone https://github.com/LordZapallo/Adopcion-Mascotas.git 
```
2. Importar Base de Datos: 
 Base de Datos Script SQL:  <a href="https://github.com/LordZapallo/Adopcion-Mascotas/blob/main/db/mascotas.sql">mascotas.sql</a>
```
Ubicacion Repositorio:  db/mascotas.sql
```
3. Instalar Dependencias:
 Donde se descargo el repositorio abrir una terminal y ejecutar:
```
npm install
composer install
```
4. Configurar archivo .env (directorio ra铆z) para conexion de base de datos.
 seguir instrucciones de par茅ntesis.
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1(insertar Host de conexi贸n)
DB_PORT=3306 (puerto de conexi贸n)
DB_DATABASE=mascotas (nombre de base de datos )
DB_USERNAME=root (usuario conexi贸n)
DB_PASSWORD=*** (contrase帽a conexi贸n)
```
5. Ejecutar Proyecto: en terminal del proyecto.
elegir una opci贸n
```
npm run watch (mantendra consola ejecutandose)
npm run dev (una sola ejecucion)
```
6. Ejecutar Servidor Laravel (composer) en otra terminal:
```
php artisan serve (matenerla ejecutando)
```
7. Abrir link de servidor artisan en navegador:
al ejecutar la sentencia anterior la terminal nos respondera la URL de ejecuci贸n de la aplicaci贸n web.  (por defecto)
```
Laravel development server started: http://127.0.0.1:8000
```
En este punto la aplicaci贸n Web estara corriendo en us servidor local.
</b>
## Cuentas de Usuario de Inicio de Sesion 馃搶
<p align="center"><img src="https://github.com/LordZapallo/Adopcion-Mascotas/blob/main/entregables/pagina-inicio.png" width="800"></p><br> 

1. Usuario Supervisor:
```
Usuario: admin@gmail.com
Contrase帽a: 123456
```
2. Usuario Regular:
```
Usuario: user@gmail.com
Contrase帽a: 123456
```
<br> 

## Detalles para Desarrolladores 鈿欙笍
La soluci贸n est谩 desarrollada con: Framework Lavarel 鈥? Vue.js 鈥? MySQL.<br> 
Para mas detalles por favor revisar Archivo: <a href="https://github.com/LordZapallo/Adopcion-Mascotas/blob/main/package.json">package.json</a>

## Licencia 馃搫
El Proyecto es una iniciativa academica por lo cual es de licencia open-sourced.
