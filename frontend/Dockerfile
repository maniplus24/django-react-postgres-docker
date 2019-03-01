FROM node:10.15.2-alpine

WORKDIR /app/frontend
COPY package.json /app/frontend

RUN npm install

EXPOSE 3000
CMD ["npm", "start"]
