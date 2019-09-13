FROM java:8-jdk-alpine

COPY ./target/article.jar /article

WORKDIR /article

RUN sh -c 'touch article.jar'

ENTRYPOINT ["java","-jar","spring-boot-demo-0.0.1-SNAPSHOT.jar"]
