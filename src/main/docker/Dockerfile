FROM java:8
VOLUME /tmp
EXPOSE 9999
ADD demo-docker-orkhan-2.jar demo-docker-orkhan-2.jar
RUN bash -c 'touch /demo-docker-orkhan-2.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/demo-docker-orkhan-2.jar"]