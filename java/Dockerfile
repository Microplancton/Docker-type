FROM maven:3.8.4-openjdk-17
WORKDIR /app
COPY pom.xml .
COPY src ./src
RUN mvn clean install
CMD ["java", "-jar", "target/my-java-app-1.0-SNAPSHOT-jar-with-dependencies.jar"]
