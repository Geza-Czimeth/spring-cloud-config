# spring-cloud-config
Cloud configuration server for microservices.
Loads properties from github repository.

### Configuration
resources/application.properties holds every configuration 

### Build
mvn clean install

### Run
java -jar target/config-server-0.0.1-SNAPSHOT.jar

Note:
Tested locally with "java 18.0.2 2022-07-19"

### Test
http://localhost:8888/order-service/default
