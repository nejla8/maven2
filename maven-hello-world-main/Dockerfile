FROM openjdk:11

COPY /target/maven-hello-world-*.jar  /app/

WORKDIR /app

ENTRYPOINT ["java","-jar","/app/maven-hello-world-*.jar"]
