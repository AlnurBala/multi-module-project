FROM alpine:latest
RUN apk add --no-cache openjdk17
COPY build/libs/ms2-0.0.1.jar /app/
WORKDIR /app/
ENTRYPOINT ["java"]
CMD ["-jar", "app.jar"]
