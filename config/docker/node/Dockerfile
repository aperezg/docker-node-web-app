FROM node:onbuild

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Bundle app source
COPY . /usr/src

EXPOSE 1703
CMD [ "npm", "start" ]


