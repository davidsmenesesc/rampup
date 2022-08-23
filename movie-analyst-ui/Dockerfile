FROM node:latest
WORKDIR /movie-analyst-ui
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3030
CMD ["node","server.js"]
