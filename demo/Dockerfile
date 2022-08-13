FROM openjdk:8-jdk-alpine
COPY target/demo-0.0.1-SNAPSHOT.jar demo-0.0.1-SNAPSHOT.jar
EXPOSE 8443
ENTRYPOINT ["java","-jar","/demo-0.0.1-SNAPSHOT.jar"]