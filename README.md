# grpc-java-generator
Maven project to generate java files from protos

* The proto files must be under src/main/proto
* The command to generate java files is mvn generate-sources

In protos, package references to its own package, base folder /proto
           java_package is the base package for the generated java classes 
