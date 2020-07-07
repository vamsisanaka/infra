FROM node:12

RUN mkdir -p /usr/local/app
WORKDIR /usr/local/app
COPY UI .
RUN chmod 774 /usr/local/app
RUN npm install
