# tacs-2c2015
TP cuatrimestral TACS

## Instalación (Para [IntelliJ](https://www.jetbrains.com/idea/download/))

Bajar la [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

Agregar ```JAVA_HOME/bin``` a nuestro ```PATH``` para que podamos usar el comando ```java```

Bajar [Maven](http://maven.apache.org/download.cgi)

Agregar ```MAVEN_HOME/bin``` a nuestro ```PATH``` y probar si funciona ```mvn -v``` 

Abrir el IntelliJ -> Import Project -> pom.xml (Tarda bastante la primera vez)

*Para iniciar el servicio*

```mvn spring-boot:run```

Si quisieramos un jar: ```mvn clean package``` y lo corremos con ```java -jar target/my-beautiful-jar.jar```