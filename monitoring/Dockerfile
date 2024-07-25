FROM openjdk:8
MAINTAINER Eric Li <ericli.xj@gmail.com>

ADD ./target/monitoring.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/monitoring.jar"]

EXPOSE 8080