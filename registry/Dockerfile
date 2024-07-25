FROM openjdk:8
MAINTAINER Eric Li <ericli.xj@gmail.com>

ADD ./target/registry.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/registry.jar"]

EXPOSE 8761