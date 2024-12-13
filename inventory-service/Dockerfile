FROM amazoncorretto:21
WORKDIR /inventory-service/app/
COPY target/inventory-service-0.0.1-SNAPSHOT.jar .
EXPOSE 80
CMD [ "java", "-jar", "inventory-service-0.0.1-SNAPSHOT.jar" ]