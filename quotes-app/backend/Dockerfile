FROM openjdk:11


WORKDIR /app

COPY . /app

RUN ./gradlew clean build

EXPOSE 8080

CMD ["java", "-jar", "build/libs/quotes-0.0.1-SNAPSHOT.jar"]