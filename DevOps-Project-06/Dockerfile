FROM eclipse-temurin:8-jre

WORKDIR /app
COPY target/demo-workshop-2.1.2.jar app.jar

EXPOSE 8000
USER 10001
ENTRYPOINT ["java", "-jar", "app.jar"]
