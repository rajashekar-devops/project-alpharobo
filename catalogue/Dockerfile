FROM node:20.19
WORKDIR /app
RUN npm install
COPY package.json .
COPY *.js .
ENV MONGO="true"
    MONGO_URL="mongodb://mongodb:27017/catalogue"
CMD ["node", "server.js"]