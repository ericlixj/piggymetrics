FROM java:8-jre
MAINTAINER Eric Li <ericli.xj@gmail.com>

ADD ./target/monitoring.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/monitoring.jar"]

EXPOSE 8080