FROM node:6.9

COPY www/ /usr/src/app/www

WORKDIR /usr/src/app/www

RUN npm install

EXPOSE 1703

CMD ["npm", "start"]
