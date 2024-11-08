FROM openjdk:17-jdk-slim

WORKDIR /app
COPY Test.java /app/test/Test.java

RUN javac /app/test/Test.java
CMD ["java", "-cp", "/app", "test.Test"]



