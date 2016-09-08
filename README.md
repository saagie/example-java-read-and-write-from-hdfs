Example for read & write into HDFS
==================

Package for saagie : mvn package and get the package in target.

Usage in local :

 - mvn package
 - java -jar target/example-java-read-and-write-from-hdfs-1.0-SNAPSHOT.jar hdfs://cluster

Usage in Saagie :

 - mvn package -Pplatform (in local, to generate jar file)
 - create new Java Job
 - upload the jar (target/example-java-read-and-write-from-hdfs-1.0-SNAPSHOT.jar)
 - copy URL from HDFS connection details panel and add it in first argument in the command line
 - choose java 8
 - create and launch.
