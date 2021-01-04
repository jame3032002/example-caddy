FROM node:12.20.0-alpine

WORKDIR /app
COPY package.json .
RUN npm install

COPY . .

ENTRYPOINT [ "npm" ]
CMD ["run", "dev"]
