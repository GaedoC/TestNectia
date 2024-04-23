# Test Prueba Nectia 
Introducción:

Se contruyerón para esta prueba 2 apis REST por el lado del back end y 1 aplicación con React Native para el front end.La applicación REACT consume como cliente la apli de Clientes desarrollada para esta prueba.

##
Tecnologías utilizadas:
##

Back End: Arquitectura API REST.
 Lenguaje de programación Java JDK 11,SpringBoot Framework, Base de datos Relacional MySql, H2 base de datos en memoria.

Front End:
 NodeJS, React native.

Repositorio GIT: https://github.com/GaedoC/TestNectia

##
Herramientas de desarrollo:
##
IDE Eclipse / SpringBoot (Descargar desde Eclipse Marketplace).
Xammp
GIT
Visual Studio Code
CLI Unix /CLI CMD
##
##
Desarrollo front end
##
React Native Aplication: my-app  
##
Requisito tener instalado nodeJS y npm.
ejecutar dentro de la carpeta Front End/my-app: 
1. npm  start
##
##
Desarrollo back End
##
Microservicio CRUD Clientes
##
Back End : Microservicio CRUD Clientes
    Desde una terminal dentro de la proyecto(/reactSpringBoot), ejecutar en órden los siguientes pasos:
##
1. mvn clean install
- Este comando Instala las dependencias y arma el Proyecto.
##
2. mvnw spring-boot:run
- Este comando ejecuta la apliación Spring boot , luego de este comando puedes probar con un request a la api de clientes.Esta api es la que consume la aplicación con React. Descargar postman colections con request de prueba de ambas apís : Postman Collection Test Request: https://github.com/GaedoC/TestNectia/tree/main/Postman%20Collection 
##
Microservicio CRUD USUARIO
##
Back End : Microservicio CRUD USUARIO
    Desde una terminal dentro de la proyecto(/nectiaTest), ejecutar en órden los siguientes pasos:
##
##
1. mvn clean install
- Este comando Instala las dependencias y arma el Proyecto.
##
2. mvnw spring-boot:run
- Este comando ejecuta la apliación Spring boot , luego de este comando puedes probar con un request a la api de usuarios.
##
Request Test:
Postman Collection Test Request: https://github.com/GaedoC/TestNectia/tree/main/Postman%20Collection

