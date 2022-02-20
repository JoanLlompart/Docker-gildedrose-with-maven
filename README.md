# Docker-gildedrose-with-maven



## Práctica de un proyecto Maven utilizando Docker

Practica docker: Docker gildedrose con Maven realizado con Matias Gomez, Arturo Garrido y Ramon Sanchez.

Primero deberemos tener un proyecto Maven o hacer un clon el siguiente repositorio https://github.com/dfleta/docker-multistage-maven-java.git 



### Creamos la imagen:

    $ docker build -t gildedrose .
    
    
 
    
##### Ejemplo:


![image](https://user-images.githubusercontent.com/91556752/154860392-87306955-528f-4d0e-81d2-8459e1e13e0c.png)


### Crear el contenedor y ejecutarlo:

    $ docker run -it --name katagildedrose gildedrose:latest
            
 
##### Ejemplo:


![image](https://user-images.githubusercontent.com/91556752/154860317-e7275aef-315f-49a9-8395-71b131dde361.png)
