Example for read & write into HDFS
==================

Package for saagie : mvn package and get the package in target.

Usage in local :

 - mvn package
 - java -jar target/example-java-read-and-write-from-hdfs-1.0-SNAPSHOT-jar-with-dependencies.jar hdfs://namenodeserver:8020

Usage in Saagie :

 - upload
 - add environment properties for HDFS uri.
 - choose java 8
 - add and launch.