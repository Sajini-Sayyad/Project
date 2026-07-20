FROM eclipse-temurin:17-jdk

WORKDIR /app

COPY target/backend-1.0-RELEASE.jar /app/backend.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/app/backend.jar"]
