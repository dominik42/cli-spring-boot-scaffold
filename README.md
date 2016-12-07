
# spring-boot-scaffold-kotlin

[![Join the chat at https://gitter.im/spring-boot-scaffold-kotlin/Lobby](https://badges.gitter.im/spring-boot-scaffold-kotlin/Lobby.svg)](https://gitter.im/spring-boot-scaffold-kotlin/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
 [![bagde](https://codeship.com/projects/e4a1d8b0-8b71-0134-1c87-26c6b97868f1/status?branch=master)](https://codeship.com/projects/184622)

#About
Generate api scaffold kotlin with spring boot rest, creating a api rest with kotlin and spring boot in an easy and productive way.

Scaffold for java web, a clean generate with simple classes.



#Structure

           __br
              __com
                  __scaffold
                           MainApplication.java
                           __domain
                                 Model.kt
                           __repository
                                 Repository.kt
                           __service
                                 Service.kt
                           __controller
                                 Controller.kt
        
#Alert
In development. Help us! Make a fork!

#Requeriments
         
* java
* Spring Boot CLI (1.4.1 or higher):

#Install
 
    $ spring version
    Spring CLI v1.4.1.RELEASE

And install the Spring Scaffold plugin

    $ mvn install
    $ spring install br.com.netodevel:spring-scaffold-cli:0.0.1-SNAPSHOT


###Todo

* validates types variables
* validates exists project,class
* set package to generate
* gradle support
* generate Test JUnit @SpringBootTest
* sample using scaffold
* add dependecies in pom.xml

###Acknowledgment
         
 * [Bruno Lima](https://github.com/brunodles)
 * [Ivan Marreta](https://github.com/ivanmarreta)
       

