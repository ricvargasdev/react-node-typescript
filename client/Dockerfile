FROM node:lts-alpine
ENV NODE_ENV=production
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm -v
RUN npm install
COPY . .
EXPOSE 3001
CMD ["npm", "start"]
