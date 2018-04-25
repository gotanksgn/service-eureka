FROM java:8
VOLUME /tmp
ADD service-eureka-0.0.1-SNAPSHOT app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]