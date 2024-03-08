FROM alpine:latest
RUN apk add --no-cache openjdk17
COPY build/libs/common-1.0.9295f94.jar /app/
WORKDIR /app/
ENTRYPOINT ["java"]
CMD ["-jar", "/app/common-1.0.9295f94.jar"]
