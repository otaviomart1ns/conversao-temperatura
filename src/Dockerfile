FROM node

WORKDIR /app

# Estruturado assim para que tenha um cache das dependencias separado do projeto
COPY package*.json .

RUN npm install 

COPY . .

EXPOSE 8080

CMD [ "node", "server.js" ]