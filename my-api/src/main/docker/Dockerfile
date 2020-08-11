FROM adoptopenjdk/openjdk11:latest
ENV my-api my-api-1.0.1.${TIMESTAMP}.jar
RUN mkdir /opt/app
COPY \$my-api /opt/app
CMD ["java", "-jar", "/opt/app/${my-api}"]
