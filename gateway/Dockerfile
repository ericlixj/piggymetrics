FROM openjdk:8
MAINTAINER Eric Li <ericli.xj@gmail.com>

ADD ./target/gateway.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/gateway.jar"]

EXPOSE 4000