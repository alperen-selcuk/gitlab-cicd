FROM openjdk:11-jre-slim-buster
EXPOSE 8080
ADD target/todo-frontend.jar /usr/local/todo-frontend/todo-frontend.jar
ENTRYPOINT ["java", "-jar", "/usr/local/todo-frontend/todo-frontend.jar"]


