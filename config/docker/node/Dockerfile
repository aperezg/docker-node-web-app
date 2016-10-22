FROM node:6.9

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY package.json /usr/src/app/
RUN npm install

COPY www /usr/src/app

EXPOSE 1703
CMD ["npm", "start"]

