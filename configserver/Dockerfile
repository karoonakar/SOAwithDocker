
FROM frolvlad/alpine-oraclejdk8
VOLUME /tmp
ADD  target/config-server1.0.jar config-server.jar
EXPOSE 9292
ENTRYPOINT ["java","-jar","/config-server.jar"]

