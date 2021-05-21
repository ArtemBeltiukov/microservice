FROM openjdk:8-jre-alpine
COPY . /usr/src
WORKDIR /usr/src
CMD ["/bin/sh", "-c", "java -Dserver.port=9091 -jar workspaces-api-0.0.1.jar"]