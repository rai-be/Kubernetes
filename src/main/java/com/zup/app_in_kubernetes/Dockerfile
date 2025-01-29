FROM openjdk:17-alpine

WORKDIR /app

COPY target/my-project.jar /app/my-project.jar

EXPOSE 8080

RUN javac HelloController.java

CMD ["java", "-jar", "my-project.jar"]
