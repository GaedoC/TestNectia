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
IDE Eclipse / SpringBoot (Descargar desde Eclipse Marketplace).
Xammp
GIT
Visual Studio Code
CLI Unix /CLI CMD / Power Shell
##
##
## Desarrollo Back End
##
Microservicio CRUD Clientes
##
Back End : Microservicio CRUD Clientes
    Desde una terminal dentro de la proyecto(/reactSpringBoot), ejecutar en órden los siguientes pasos:
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
Microservicio CRUD USUARIO
##
Back End : Microservicio CRUD USUARIO
    Desde una terminal dentro de la proyecto(/nectiaTest), ejecutar en órden los siguientes pasos:
##
1. mvn clean install
- Este comando Instala las dependencias y arma el Proyecto.
##
2. mvnw spring-boot:run
- Este comando ejecuta la apliación Spring boot , luego de este comando puedes probar con un request a la api de usuarios.
##
## Postman Collection
Request Test:
Postman Collection Test Request: https://github.com/GaedoC/TestNectia/tree/main/Postman%20Collection
##
Create
![image](https://github.com/GaedoC/TestNectia/assets/17816969/26676798-597e-4843-a422-e66e4f939933)
Edit
![image](https://github.com/GaedoC/TestNectia/assets/17816969/e9e4ba2e-9735-407b-91d5-9d2dfa057532)
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
![image](https://github.com/GaedoC/TestNectia/assets/17816969/a8904f7b-dd82-461d-8407-846d38ddf643)


