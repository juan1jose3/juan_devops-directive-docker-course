FROM node

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

USER node

# copy from source to working directory
COPY ./src .


CMD ["node", "index.js"]


