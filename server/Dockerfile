FROM adoptopenjdk/openjdk11:alpine

WORKDIR /app

ADD build/libs/server-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "/app.war"]





