FROM openjdk:8
MAINTAINER Eric Li <ericli.xj@gmail.com>

ADD ./target/notification-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/notification-service.jar"]

EXPOSE 8000