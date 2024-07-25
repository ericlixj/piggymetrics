FROM openjdk:8
MAINTAINER Eric Li <ericli.xj@gmail.com>

ADD ./target/statistics-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/statistics-service.jar"]

EXPOSE 7000