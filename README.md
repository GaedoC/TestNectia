# Test Prueba Nectia 
Introducción:

Se contruyerón para esta prueba 2 apis REST por el lado del back end y 1 aplicación con React Native para el front end.La applicación REACT consume como cliente la apli de Clientes desarrollada para esta prueba.

##
## Tecnologías utilizadas:
##

Back End: Arquitectura API REST. 
 Lenguaje de programación Java JDK 11,SpringBoot Framework, Base de datos Relacional MySql, H2 base de datos en memoria.

Front End:
 NodeJS, React native.

Repositorio GIT: https://github.com/GaedoC/TestNectia

##
## Herramientas de desarrollo:
##
IDE Eclipse / SpringBoot (Descargar desde Eclipse Marketplace) o Power Shell, 
Visual Studio Code o Power Shell,
GIT y GitHub
##
##
## Desarrollo Back End
##
Microservicio CRUD Clientes
##
Back End : API REST CRUD Clientes
    Desde una terminal dentro del proyecto y dentro de la carpeta del proyecto " ./reactSpringBoot" con CMD o PowerShell ejecutar en el órden los siguientes comandos:
##
1. mvn clean install
- Este comando Instala las dependencias y arma el Proyecto.

![image](https://github.com/GaedoC/TestNectia/assets/17816969/9723ff3b-c729-4dd1-9cc9-07e8b9f23e67)
![image](https://github.com/GaedoC/TestNectia/assets/17816969/0980be1c-c9d1-4753-8950-6f020e0820d2)
##
2. mvnw spring-boot:run
- Este comando ejecuta la apliación Spring boot , luego de este comando puedes probar con un request a la api de clientes.Esta api es la que consume la aplicación con React. Descargar postman colections con request de prueba de ambas apís : Postman Collection Test Request: https://github.com/GaedoC/TestNectia/tree/main/Postman%20Collection.

![image](https://github.com/GaedoC/TestNectia/assets/17816969/5d6a5d1c-9c01-477c-b831-c3d4c5f9cd63)
![image](https://github.com/GaedoC/TestNectia/assets/17816969/040e4bd4-0db6-4ceb-a067-60bbb4fc75cf)
##
##
## Postman Collection
Request Test:
Postman Collection Test Request: https://github.com/GaedoC/TestNectia/tree/main/Postman%20Collection
##
Create
![image](https://github.com/GaedoC/TestNectia/assets/17816969/26676798-597e-4843-a422-e66e4f939933)
Edit
![image](https://github.com/GaedoC/TestNectia/assets/17816969/bee70268-ce71-4297-b34b-ac160a74894b)
Listar Todos
![image](https://github.com/GaedoC/TestNectia/assets/17816969/cbb8be31-584f-4442-926c-7326f55aeafd)

##
## Desarrollo Front End
##
React Native Aplication: my-app  
##
RequisitoS:
  - Tener instalado nodeJS y npm
  - Tener Ejecutando Api CRUD Clientes.

ejecutar dentro de la carpeta Front End/my-app: 
1. npm  start
![image](https://github.com/GaedoC/TestNectia/assets/17816969/f808eb1e-f3b0-4220-954b-ea36ddde0408)

Desde el navegador se visualizaría así:
Crear un cliente
![image](https://github.com/GaedoC/TestNectia/assets/17816969/80258b68-e2d5-40a6-bc1c-9b580c68926f)
Listar Cliente
![image](https://github.com/GaedoC/TestNectia/assets/17816969/02a5aa90-2a1a-45e8-8dc3-2e6b25ece576)
Eliminar Cliente
![image](https://github.com/GaedoC/TestNectia/assets/17816969/0086e6d9-4b2f-4998-aedb-c3e296295d60)
Editar Cliente
![image](https://github.com/GaedoC/TestNectia/assets/17816969/fdffcb5c-aae4-4a42-9ce2-67673392c391)
##
##
## Base de datos 
##
Crear Base de datos de nombre : "nectiadb". Esta Base de datos la utilizará la api REST de usuarios.
Importar Script de la base de datos que esta en repo: https://github.com/GaedoC/TestNectia/blob/main/Base%20de%20datos/nectiadb.sql y ejecutar desde una base datos MySQL.

![image](https://github.com/GaedoC/TestNectia/assets/17816969/51eaa9dc-77d9-4ded-a36a-32b0e75dc3e4)

Consulta tabla users:
![image](https://github.com/GaedoC/TestNectia/assets/17816969/9e771163-6dc1-4f2c-8246-830c41cb667a)

Credenciales:Deben ser las mismas que el archivo application.properties de la api de usuarios.

Data Base:nectiadb
User:root
Password: 

Archivo: application.properties
![image](https://github.com/GaedoC/TestNectia/assets/17816969/d91a0854-fa6f-4cfc-a45c-33e79cf39c4d)

##
##
## API REST CRUD USUARIO 
##
Back End : API REST CRUD USUARIO
    Desde una terminal dentro de la proyecto(/nectiaTest), ejecutar en órden los siguientes pasos:
##
1. mvn clean install
- Este comando Instala las dependencias y arma el Proyecto.
- ![image](https://github.com/GaedoC/TestNectia/assets/17816969/6aebf247-13a0-4ebb-afc6-e81143b735b3)
- ![image](https://github.com/GaedoC/TestNectia/assets/17816969/ec742219-f8bf-4de6-b169-e04c16175177)

##
2. mvnw spring-boot:run
- Este comando ejecuta la apliación Spring boot , luego de este comando puedes probar con un request a la api de usuarios.
- ![image](https://github.com/GaedoC/TestNectia/assets/17816969/6d75fc94-70d3-4665-aed5-4e2085f03331)
![image](https://github.com/GaedoC/TestNectia/assets/17816969/d7168b78-f636-4f5a-8750-d67842e442fa)
##


