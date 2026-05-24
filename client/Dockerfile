FROM node:20-alpine

WORKDIR /src

COPY packege*.json ./

RUN npm install

COPY . .

EXPOSE 5173

CMD ["npm","run", "dev", "--", "--host"]
