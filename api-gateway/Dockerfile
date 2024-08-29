FROM openjdk:17
VOLUME /tmp
COPY target/api-gateway-1.0-SNAPSHOT.jar api-gateway.jar
ENTRYPOINT ["java", "-jar", "/api-gateway.jar"]
