FROM openjdk:17
RUN mkdir /app
WORKDIR /app
COPY target/user-service-0.0.1-SNAPSHOT.jar /app
EXPOSE 8081

ENTRYPOINT ["java", "-jar", "user-service-0.0.1-SNAPSHOT.jar"]
