# concesionario
Sistema ó Aplicativo Web para un gestionar una red de Concesionarios en Venezuela..

La empresa de Automóviles, desea tener un sistema de información que le permita llevar el control
de sus clientes. Actualmente la empresa posee una red de concesionarios a nivel nacional,
alrededor de 15. Pero requiere tener un sistema que le permite gestionar la información de sus
clientes y segmentar los mismos por concesionario.

Requisitos del Sistema necesario
- Se requiere el desarrollo de un aplicativo Web para llevar el control de la gestión de clientes para el sector
automotriz, para los concesionarios de vehículos a nivel nacional en las principales ciudades.
- Desarrollar el aplicativo a través de las operaciones básicas de un CRUD (crear, consultar, modificar y
eliminar), para gestionar la información de los clientes y que se registre el cliente según la localidad.
- El aplicativo debe manejar un repositorio con cualquier motor de base de datos con interfaz al aplicativo.
- Se requiere obtener un reporte de los clientes por concesionario y por localidad. Deseable, permitir exportar la
información del reporte en un formato PDF.
- Si se requiere eliminar un cliente, el mismo debe cambiar de estatus a inactivo. No debe eliminarse de la BD.

//-------------------------------------------
//-------------------------------------------
//-------------------------------------------

Requerimientos del Aplicativo Web
- Crear una Base de Datos llamada concesionario
- Ejecutar el script llamado conscesionario.sql para generar las tablas e insertar datos de prueba..
- Datos necesarios para acceso a base de datos, se pueden modifcar en el archivo db_conection.php ubicaso en la carpeta 'general'
		- $host="localhost";
		- $user="root";
		- $password="";
		- $db="concesionario";
- Ingresar al sistema con cualquiera de los siguientes perfiles de prueba



- Perfil_100 	user=100@gmail.com  	      pass=100    
- Perfil_200 	user=200@gmail.com  	      pass=200    
- Perfil_300 	user=300@gmail.com  	      pass=300    

