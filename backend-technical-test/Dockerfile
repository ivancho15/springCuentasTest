FROM openjdk:21-jdk
ARG JAR_FILE=target/spring-boot-technical-test-0.0.1.jar
COPY ${JAR_FILE} spring-boot-technical-test-0.0.1.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "spring-boot-backend-apirest.jar"]