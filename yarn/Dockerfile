FROM node:latest
RUN apt-get update && apt-get install apt-transport-https -y
RUN apt-get update && curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | apt-key add - \
    && echo "deb https://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list \
    && apt-get update && apt-get -y install yarn
ARG DIR_NAME="code"

RUN mkdir "/${DIR_NAME}"
WORKDIR "/${DIR_NAME}"
