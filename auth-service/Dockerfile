FROM openjdk:8
MAINTAINER Eric Li <ericli.xj@gmail.com>

ADD ./target/auth-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/auth-service.jar"]

EXPOSE 5000