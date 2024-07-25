FROM openjdk:8
MAINTAINER Eric Li <ericli.xj@gmail.com>

ADD ./target/account-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/account-service.jar"]

EXPOSE 6000