FROM openjdk:11-slim

LABEL maintainer="Murat Deniz Alioglu <mdenizalioglu@gmail.com>"

ARG JAR_FILE

COPY ${JAR_FILE} app.jar

ENTRYPOINT ["java", "-jar", "/app.jar"]