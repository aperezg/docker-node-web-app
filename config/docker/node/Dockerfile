FROM node:6.9

RUN mkdir -p /usr/src/app
COPY www /usr/src/app/www
COPY package.json /usr/src/app/
WORKDIR /usr/src/app

RUN npm install

EXPOSE 1703
CMD ["npm", "start"]

