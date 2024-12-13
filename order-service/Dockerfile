FROM amazoncorretto:21
WORKDIR /order-service/app/
COPY target/order-service-0.0.1-SNAPSHOT.jar .
EXPOSE 80
CMD [ "java", "-jar", "order-service-0.0.1-SNAPSHOT.jar" ]