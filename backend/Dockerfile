FROM openjdk:11-jre-slim-buster

EXPOSE 8081

ADD target/todo-backend.jar /usr/local/todo-backend/todo-backend.jar

ENTRYPOINT ["java", "-jar", "/usr/local/todo-backend/todo-backend.jar"]


