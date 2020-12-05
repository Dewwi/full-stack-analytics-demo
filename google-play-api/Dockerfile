FROM node:12.18.1

ENV NODE_ENV=production

WORKDIR /app
RUN git clone https://github.com/facundoolano/google-play-api.git .

RUN npm install --production

CMD [ "npm", "start" ]
