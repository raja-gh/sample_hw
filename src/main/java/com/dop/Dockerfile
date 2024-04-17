#FROM ubuntu:latest

#RUN apt-get update && apt-get install sudo 

FROM openjdk:17-slim

#RUN mkdir -p /opt/app

WORKDIR /app

COPY com.hw-0.0.1-SNAPSHOT.jar /app

# Specify the container port
EXPOSE 80

#RUN cd /home/raja/eclipse-workspace/com.hw/target/ && cp com.hw-0.0.1-SNAPSHOT.jar /opt/app/

CMD ["java", "-jar", "/app/com.hw-0.0.1-SNAPSHOT.jar"]
