FROM eclipse-temurin:17-jre

# Set working directory inside the container
WORKDIR /app

ARG JAR_FILE=target/cicdjava-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app.jar

ENTRYPOINT ["java","-jar","app.jar"]
