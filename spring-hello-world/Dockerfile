FROM openjdk:11

WORKDIR /app

COPY . /app

RUN ./gradlew clean build

ARG JAR_FILE


EXPOSE 8080

CMD ["java", "-jar", "/app/build/libs/spring-hello-world-0.0.1-SNAPSHOT.jar"]