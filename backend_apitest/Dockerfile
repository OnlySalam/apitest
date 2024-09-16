FROM node:alpine
RUN mkdir -p /home/backend

WORKDIR /home/backend
COPY package.json .

RUN npm install

COPY . .

EXPOSE 90

ENV PORT=90

ENTRYPOINT ["node", "backend_sample.js"]