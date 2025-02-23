FROM eclipse-temurin:21-jdk

WORKDIR /backend

COPY .mvn ./.mvn
COPY mvnw .
COPY mvnw.cmd .
COPY pom.xml .
COPY src ./src

EXPOSE 8081

ENTRYPOINT ["./mvnw","quarkus:dev"]

