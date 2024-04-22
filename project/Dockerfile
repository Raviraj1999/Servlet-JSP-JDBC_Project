#base image
FROM openjdk:8
WORKDIR /app
COPY . /app/
RUN javac Login.java
ENTRYPOINT ["java", "Main"]