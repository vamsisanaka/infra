FROM node:latest

RUN mkdir -p /usr/local/app
WORKDIR /usr/local/app
COPY UI .
RUN chmod 774 /usr/local/app
EXPOSE 8080
RUN yarn install
ENTRYPOINT ["yarn", "start"]
