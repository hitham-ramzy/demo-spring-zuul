# demo-spring-zuul
This application is an api gateway for alten demo application, using spring eureka client, actuator and zuul proxy.

## Using Docker to simplify development

You can also fully dockerize your application and all the services that it depends on.
To achieve this, first build a docker image, Please run:

    mvn package docker:build -X

Then run:

    docker-compose -f src/main/docker/app.yml up -d

## Close Docker container

To close docker container, Please run:
    
    docker-compose -f src/main/docker/app.yml down