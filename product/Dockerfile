FROM node:22-alpine3.18
WORKDIR /app
COPY package.json /app
RUN npm install
ADD . /app
CMD ["npm","start"]
