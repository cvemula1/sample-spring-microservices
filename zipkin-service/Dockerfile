FROM openjdk
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/*.jar zipkin-service.jar
ENTRYPOINT ["java", "-jar", "/zipkin-service.jar"]
EXPOSE 9411
