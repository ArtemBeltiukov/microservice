FROM openjdk:8-jre-alpine
COPY . /usr/src
WORKDIR /usr/src
CMD ["/bin/sh", "-c", "java -jar -Dserver.port=9090 workspaces-api-0.0.1.jar"]