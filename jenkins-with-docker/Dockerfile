FROM jenkins/jenkins:alpine
USER root
RUN apk add --no-cache docker-cli docker-compose
RUN addgroup -g 101 docker
RUN addgroup jenkins docker
USER jenkins
