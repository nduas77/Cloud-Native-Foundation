# set the base image
FROM node:alpine

# set the working directory
WORKDIR '/app'

# install dependencies
COPY package.json app.js ./
RUN npm install

# expose the port
EXPOSE 8080

# default commands
CMD ["npm", "start"]
