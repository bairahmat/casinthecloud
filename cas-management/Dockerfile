FROM openjdk:8u121-jdk-alpine

COPY ./target/cas-management.war /target/

EXPOSE 8081
CMD ["java", "-jar", "-Xms256m", "-Xmx256m", "target/cas-management.war"]
