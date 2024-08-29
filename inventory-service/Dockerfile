FROM openjdk:17
VOLUME /tmp
COPY target/inventory-service-1.0-SNAPSHOT.jar inventory-service.jar
ENTRYPOINT ["java", "-jar", "/inventory-service.jar"]
