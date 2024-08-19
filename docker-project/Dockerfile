FROM openjdk:17-alpine
EXPOSE 8080
ARG JAR_FILE
ADD ${JAR_FILE} /app.jar
CMD ["java", "-jar", "/app.jar"]

