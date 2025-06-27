FROM node:8.9.3-alpine
LABEL maintainer="Ramakrishna azureramakrishna@gmail.com"
RUN mkdir -p /usr/src/app
COPY ./* /usr/src/app/
WORKDIR /usr/src/app
RUN npm install
CMD ["node", "/usr/src/app/index.js"]
