FROM openjdk:8-jre-alpine

MAINTAINER Hitham Ramzy <hitham.ramzy@gmail.com>

COPY alten-zuul.jar alten-zuul.jar

EXPOSE 9871

ENTRYPOINT ["java","-Deureka.client.serviceUrl.defaultZone=http://eureka-service:8761/eureka/","-jar", "/alten-zuul.jar"]