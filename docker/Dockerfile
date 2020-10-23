FROM node:7
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
CMD node hello.js
EXPOSE 9000