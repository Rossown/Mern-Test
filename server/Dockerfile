FROM node:15.3

#Crreat app directory
WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install --silent

COPY . .
EXPOSE 5000

CMD ["npm", "start"]