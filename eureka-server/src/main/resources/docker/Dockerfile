#这个文件是干什么用的???
FROM livingobjects/jre8
VOLUME /tmp
ADD eureka-server-1.0.0-SNAPSHOT.jar app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 8761
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
