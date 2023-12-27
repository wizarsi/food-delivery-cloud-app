#define base docker image
FROM openjdk:17
ADD target/api-auth-0.0.1-SNAPSHOT.jar api-auth-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "api-auth-0.0.1-SNAPSHOT.jar"]