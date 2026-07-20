FROM eclipse-temurin:17-jdk

WORKDIR /app

COPY target/frontend-1.0-RELEASE.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]
