FROM node:20-alpine

WORKDIR /React404

COPY ./React_404/cvs-app/package.json .

RUN npm install

COPY . .

EXPOSE 3000

RUN npm config set proxy http://team3spring:8080

CMD ["npm", "start"]
