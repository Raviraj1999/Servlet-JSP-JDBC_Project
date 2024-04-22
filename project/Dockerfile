#base image
FROM openjdk:8
WORKDIR /app
COPY . /app/
RUN javac login.jsp
ENTRYPOINT ["java", "Main"]