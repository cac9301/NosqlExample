# Contador-de-palabras

# Hadoop- yarn- Mapreduce- hdfs

# Run on Codenvy 

FROM [codenvy/ubuntu_jdk8](https://hub.docker.com/r/codenvy/hadoop-dev/)

# Commands

1. Para correr el programa debe generar una maquina en codenvy, ya generada importamos el proyecto y lo montamos en el workspace
2. ejecutamos el siguiente comando para correr maven.
```
mvn -f /projects/NosqlExample clean install
```
3. ejecutamos el siguiente comando para correr hadoop con su repectivo jre.
```
cd /projects/NosqlExample
mvn exec:java -Dexec.mainClass='org.eclipse.che.wordcount.WordCount'
```

En el link a continuacion hay un video en donde se muestran los pasos a seguir.



# Forma local 
Este ejemplo por su sencillez es conocido como el "hello world" de hadoop y y MapReduce.
si deseas correrlo en local tener en cuenta 

mvn clean install 

# 1: Se crea proyecto en java applications
mvn exec:java -Dexec.mainClass="com.javacodegeeks.examples.wordcount.WordCoun

# 2 las variables de entorno las cuales tienes que tener instaladas 
http://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-2.7.7/hadoop-2.7.7.tar.gz

el jdk de java
https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html?ssSourceSiteId=otnes

un editor de codigo como neatbeans o eclipse y instalar las dependencia 
Se instala hadoop se ingresa a la carpeta donde esta instalado y ingresa a las carpetas correspondientes
hadoop/share/hadoop/common 

# 3:Se instala hadoop se ingresa a la carpeta donde esta instalado y ingresa a las carpetas correspondientes
hadoop/share/hadoop/common 

# 4:agrega las librerias que se ven en la carpeta las cuales son
```bash
hadoop-common-2.8.2.jar
hadoop-common-2.8.2.test.jar
hadoop-nfs-2.8.2.jar
```
# 5:despues de agregar estas librerias el siguiente paso es agregar las librerias de otra carpeta
hadoop/share/hadoop/mapreduce
las librerias son
```bash
hadoop-mapreduce-client-app-2.8.2.jar
hadoop-mapreduce-client-common-2.8.2.jar
hadoop-mapreduce-client-core-2.8.2.jar
hadoop-mapreduce-client-hs-2.8.2.jar
hadoop-mapreduce-client-hs-plugins-2.8.2.jar
hadoop-mapreduce-client-jobclient-2.8.2.jar
hadoop-mapreduce-client-jobclient-2.8.2-test.jar
hadoop-mapreduce-client-shuffle-2.8.2.jar
```
