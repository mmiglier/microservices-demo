FROM java:8
VOLUME /tmp
ADD accounts.jar app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 2222
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]