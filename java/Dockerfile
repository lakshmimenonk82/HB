#### Stage 2: A minimal docker image with command to run the app
FROM openjdk:11

# Copy project dependencies from the build stage
COPY build/libs/realworld-spring-boot-java-2.1.1.jar  realworld-2.1.1.jar

ENTRYPOINT ["java","-jar","/realworld-2.1.1.jar"]