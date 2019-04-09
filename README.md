# Contador-de-palabras

# Hadoop- yarn- Mapreduce- hdfs

# Run on Codenvy 

FROM [codenvy/ubuntu_jdk8](https://hub.docker.com/r/codenvy/hadoop-dev/)

# Commands

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Build and Run | `cd ${current.project.path} && mvn clean install && mvn exec:java -Dexec.mainClass="com.javacodegeeks.examples.wordcount.WordCount"` |

# Otro si 
si deseas correrlo en local tener en cuenta 
mvn clean install
mvn exec:java -Dexec.mainClass="com.javacodegeeks.examples.wordcount.WordCoun

las variables de entorno las cuales tienes que tener instaladas 
http://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-2.7.7/hadoop-2.7.7.tar.gz

el jdk de java
https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html?ssSourceSiteId=otnes

un editor de codigo como neatbeans o eclipse
y instalar las dependencia 


