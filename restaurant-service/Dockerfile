#define base docker image
FROM openjdk:17
ADD target/restaurant-service-0.0.1-SNAPSHOT.jar restaurant-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "restaurant-service-0.0.1-SNAPSHOT.jar"]