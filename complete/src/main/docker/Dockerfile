FROM java:7
VOLUME /tmp
ADD gs-spring-boot-docker-0.1.0.jar app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 8080
EXPOSE 18080

ENTRYPOINT java -Djava.security.egd=file:/dev/./urandom -jar $JAVA_OPT_DEV /app.jar

