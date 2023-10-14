# Base Image
FROM node:20 

WORKDIR /usr/src/app

COPY package* .

RUN npm install

COPY . .

EXPOSE 3000
# This only runs when we are Running the image i.e before we start the container
CMD ["node", "index.js"]



