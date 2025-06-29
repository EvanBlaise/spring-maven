FROM eclipse-temurin:17-jdk-jammy

WORKDIR /app

# Copie du JAR généré par Maven
COPY target/demo-github-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
