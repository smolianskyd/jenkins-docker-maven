FROM adoptopenjdk/openjdk11:latest
RUN mkdir /opt/app
COPY /var/jenkins_home/workspace/timestamp/my-api/target/my-api-1.0.1.*.jar /opt/app/my-api.jar
CMD ["java", "-jar", "/opt/app/my-api.jar"]