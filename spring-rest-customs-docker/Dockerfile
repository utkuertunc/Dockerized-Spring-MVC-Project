FROM java:8-jdk-alpine

COPY ./target/msproducts 0.0.1-SNAPSHOT.jar /usr/app/

WORKDIR /usr/app

RUN sh -c 'touch msproducts 0.0.1-SNAPSHOT.jar'

ARG JAR_FILE=target/msproducts 0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","msproducts 0.0.1-SNAPSHOT.jar"]