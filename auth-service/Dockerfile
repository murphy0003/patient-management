FROM gradle:9.0.0-jdk-21-and-24-alpine as builder

WORKDIR /app

COPY gradle/ gradle/
COPY build.gradle .

RUN apk add --no-cache gcompat

RUN gradle dependencies --no-daemon

COPY src/ ./src

RUN gradle clean build -x test --no-daemon

# Runtime stage
FROM eclipse-temurin:21-jre as runner

WORKDIR /app

# Copy the jar file (assuming standard Spring Boot naming convention)
COPY --from=builder /app/build/libs/*.jar app.jar

EXPOSE 4005

ENTRYPOINT ["java", "-jar", "app.jar"]