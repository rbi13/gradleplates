FROM openjdk:8-jre-alpine
MAINTAINER rbi13

ENV MAIN_CLASS='io.rbi.tpl8.Main'
COPY build/libs /app/libs
WORKDIR /app
CMD java -cp "libs/*" ${MAIN_CLASS}
