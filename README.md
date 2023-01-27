# spring-cloud-config
Cloud configuration server for microservices.
Loads properties from github repository.

### Configuration
resources/application.properties holds every configuration 

### Build
mvn clean install

### Run
java -jar target/config-server-0.0.1-SNAPSHOT.jar

### Test
http://localhost:8888/order-service/default
