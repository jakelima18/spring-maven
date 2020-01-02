FROM openjdk:8-jdk-alpine
VOLUME /tmp
WORKDIR /app
COPY target/gs-spring-boot-docker-0.1.0.jar gs-spring-boot-docker-0.1.0.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app/gs-spring-boot-docker-0.1.0.jar"]