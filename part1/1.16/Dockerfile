FROM amazoncorretto:17

EXPOSE 8080

COPY . .

RUN chmod +x mvnw
RUN ./mvnw package

CMD ["java", "-jar", "./target/dockerDemo-0.0.1-SNAPSHOT.jar"]
 