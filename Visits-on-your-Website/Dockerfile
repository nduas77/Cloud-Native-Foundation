# set the base image
FROM node:alpine

# set the working directory
WORKDIR '/app'

# install dependencies
COPY package.json .
RUN npm install
COPY . .

# expose the port
EXPOSE 8080

# default commands
CMD ["npm", "start"]
