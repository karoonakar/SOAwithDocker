
FROM frolvlad/alpine-oraclejdk8
VOLUME /tmp
ADD  target/eureka-server-1.0.jar eureka-server.jar
EXPOSE 9090
ENTRYPOINT ["java","-jar","/eureka-server.jar"]

