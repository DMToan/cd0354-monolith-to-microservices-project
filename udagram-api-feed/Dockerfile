FROM --platform=linux/amd64 node:16.18.0
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm ci 
COPY . .
EXPOSE 8080
CMD [ "npm", "run", "prod" ]