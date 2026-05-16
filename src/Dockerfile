FROM eclipse-temurin:25

WORKDIR /app

COPY target/product-api-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8081

ENTRYPOINT ["java", "-jar", "app.jar"]