FROM amazoncorretto:21-alpine-jdk

WORKDIR /app

ADD target/project-service.jar app.jar

EXPOSE 9083

ENTRYPOINT ["java", "-jar", "app.jar"]