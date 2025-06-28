FROM eclipse-temurin:17-jdk-jammy
WORKDIR /app

# le jar aura été copié sous le nom app.jar
COPY app.jar app.jar  

EXPOSE 8080
ENTRYPOINT ["java","-jar","app.jar"]
