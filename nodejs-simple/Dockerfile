FROM node:alpine

WORKDIR /usr/app

COPY ./package.json ./

RUN npm install

COPY ./ ./

CMD ["npm", "start"]

#docker build -t paihari/nodejs-simple .
#docker run paihari/nodejs-simple
#docker run -p 8080:8080 paihari/nodejs-simple

#To Open shell on coantiner
#docker run -it paihari/nodejs-simple sh
#docker exec -it 305b5ab7a55e sh





