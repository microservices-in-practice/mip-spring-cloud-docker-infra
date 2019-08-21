FROM openjdk:8-jre-alpine
COPY maven/*.jar /app.jar
EXPOSE 8888
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
