# tacs-2c2015
TP cuatrimestral [TACS](https://docs.google.com/document/d/1QVK2Ua9IBlcdvLbIWmJsNY2Ev5bSSBdmugOwHuchMhE/pub)

## Instalación (Para [IntelliJ](https://www.jetbrains.com/idea/download/))

1) Bajar la [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

Agregar ```JAVA_HOME/bin``` a nuestro ```PATH``` para que podamos usar el comando ```java```.
Para eso abrir el ```~/.bashrc``` o ```~/.zshrc``` y agregar al final ```export JAVA_HOME=aca/el/path```

2) Bajar [Maven](http://maven.apache.org/download.cgi)

Agregar ```MAVEN_HOME/bin``` a nuestro ```PATH``` y probar si funciona ```mvn -v``` 

3) Abrir el IntelliJ -> Import Project -> pom.xml (Tarda bastante la primera vez)

*Para iniciar el servicio desde el root del proyecto*

```mvn spring-boot:run```

Si quisieramos un jar: ```mvn clean package``` y lo corremos con ```java -jar target/my-beautiful-jar.jar```
