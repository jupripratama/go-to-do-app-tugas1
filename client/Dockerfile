FROM node:its-apline

WORKDIR /app
COPY package.json .

RUN npm install
COPY . .
CMD ["npm", "start"]

