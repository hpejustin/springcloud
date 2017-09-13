FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/docker-1.0-SNAPSHOT.jar app.jar
ENTRYPOINT [ "sh", "-c", "java -jar /app.jar" ]