
FROM adoptopenjdk/openjdk11:alpine-jre

ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} customertype.jar
ENTRYPOINT ["java","-jar","/customertype.jar"]
