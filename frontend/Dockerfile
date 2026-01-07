FROM node:21-slim

WORKDIR /app

COPY . .

RUN npm i

COPY . .

EXPOSE 5173

CMD ["npm", "run", "dev", "--", "--host"]
