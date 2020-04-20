FROM openjdk:8-jre-alpine
MAINTAINER rashmit.rathod@gmail.com
ADD target/springboot-prometheus-hello-world-1.0.jar /opt/
RUN chmod 777 /opt/springboot-prometheus-hello-world-1.0.jar
CMD ["java","-jar","/opt/springboot-prometheus-hello-world-1.0.jar"]
