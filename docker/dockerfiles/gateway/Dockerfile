FROM openjdk:8-jre-alpine
COPY . /usr/src
WORKDIR /usr/src
CMD ["/bin/sh", "-c", "java -jar -Dserver.port=9094 api-gateway-0.1.0.jar"]