FROM node:14.15.0

COPY . /App/frontend
WORKDIR /App/frontend

RUN npm install && cp .env.default .env

CMD ["npm", "start"]



