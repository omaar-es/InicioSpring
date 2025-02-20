# Tarea 1.- Herramientas para el desarrollo de proyectos de Software
####  Instalación y configuración de herramientas para trabajar con Spring boot

###### A continuación se muestra el contenido en esta sección:
1. Instalación y configuración de las siguientes herramientas:
		 JDK (Versión Amazon Coretto)
		 Maven
		 Spring Boot (Spring Initializr)
		 Git
		 Xampp
2. Validación de instalación
3. Prueba del endpoint desde el navegador
4. Como ejecutar el proyecto 

#### 1. Instalación y configuración 
###### JDK
>  Instalar Open JDK en su versión Coretto

Vamos al sitio de AWS a descargar el JDK en su versión 21, se nos creara la variable de entorno de forma automática
![](https://github.com/omaar-es/InicioSpring/blob/main/img/jdk.png?raw=true)

###### Maven

>  Instalar Maven desde la pagina oficial: 

![](https://github.com/omaar-es/InicioSpring/blob/main/img/maven.png?raw=true)
A continuación se descargara un archivo Zip que contiene los archivos correspondientes

> Copiar la carpeta en el disco local C

Una vez se tienen la carpeta de Maven, ahora se coloca en una carpeta del disco local C
![](https://github.com/omaar-es/InicioSpring/blob/main/img/MAVEN-ARCHIVO.png?raw=true)

> Agregar la variable al path

Se copia la ruta en donde se encuentra la carpeta de Maven y a continuación se agrega como una nueva variable de entorno. 
![](https://github.com/omaar-es/InicioSpring/blob/main/img/variableMaven.png?raw=true)

Luego nos vamos al path para agregar la nueva variable que hemos creado
![](https://github.com/omaar-es/InicioSpring/blob/main/img/AgregarPathMaven.png?raw=true)

###### Spring Boot (Spring Initializr)
En nuestro IDE de preferencia instalamos la extensión de Spring Initializr, esto nos ayudará a crear los proyectos de spring de una manera rápida
![](https://github.com/omaar-es/InicioSpring/blob/main/img/springInitializr.png?raw=true)

###### Git 
> Descargar git desde la página oficial: https://git-scm.com/downloads/win

A continuación se descarga el ejecutable.

![](https://github.com/omaar-es/InicioSpring/blob/main/img/GIT.png?raw=true)
###### Xampp
> Descargar xampp desde la página oficial: https://www.apachefriends.org/es/download.html
![](https://github.com/omaar-es/InicioSpring/blob/main/img/xampp.png?raw=true)
A continuación se descarga el ejecutable para su instalación

> Iniciamos Xampp a través de xampp Control

Buscamos en la carpeta de Xampp un ejecutable llamado xampp control
![](https://github.com/omaar-es/InicioSpring/blob/main/img/xamppControl.png?raw=true)


#### 2. Validación de instalación
###### JDK
>  Escribimos en la terminal "java -version" Open JDK en su versión Coretto para validar que este instalado de forma correcta
![](https://github.com/omaar-es/InicioSpring/blob/main/img/validacion-java.png?raw=true)
###### MAVEN
>  Escribimos en la terminal "mvn  -version" Open JDK en su versión Coretto para validar que este instalado de forma correcta

![](https://github.com/omaar-es/InicioSpring/blob/main/img/maven-validacion.png?raw=true)


#### 3. Prueba del endpoint desde el navegador
Escribimos desde el navegador de nuestra preferencia lo siguiente: "*localhost:8080*"
El puerto 8080 es el que esta predefinido por defecto
![](https://github.com/omaar-es/InicioSpring/blob/main/img/springEndpoint.png?raw=true)

#### 4. Como ejecutar el proyecto
> 1. Escribimos en nuestra terminal el siguiente comando: ***mvn spring-boot:run***

![](https://github.com/omaar-es/InicioSpring/blob/main/img/runJava.png?raw=true)

> 2.Escribimos en el navegador ***localhost:8080***

Nos dirigiremos al login de spring security en donde encontraremos nuestra contraseña en la terminal. La contraseña la podemos encontrar en la terminal:

![](https://github.com/omaar-es/InicioSpring/blob/main/img/passwordSpring.png?raw=true)

![](https://github.com/omaar-es/InicioSpring/blob/main/img/loginSpring.png?raw=true)
