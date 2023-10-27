FROM openjdk:11

COPY . ./app
WORKDIR /app


RUN ./gradlew clean build

#ARG JAR_FILE



#CMD ["java", "-jar", "/app/build/libs/products-api-0.0.1-SNAPSHOT.jar"]