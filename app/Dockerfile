FROM node:latest

#create app directory
WORKDIR "/app"

COPY package.json ./

RUN npm install

COPY index.js /app

EXPOSE 80

CMD ["node", "index.js"]