FROM maven:3.8.4-jdk-11-slim as builder
WORKDIR /app

EXPOSE 80
RUN mvn dependency:resolve
RUN mvn package
COPY --from=builder /app/target/worker-jar-with-dependencies.jar .

FROM openjdk:11-jre-slim

CMD ["java", "-jar", "worker-jar-with-dependencies.jar"]
