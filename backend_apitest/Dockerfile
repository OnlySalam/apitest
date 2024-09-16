FROM node:alpine
RUN mkdir -p /home/backend

WORKDIR /home/backend
COPY package.json .

RUN npm install

COPY . .

EXPOSE 9091

ENV PORT=9091

ENTRYPOINT ["node", "backend_sample.js"]