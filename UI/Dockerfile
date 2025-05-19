FROM node:17
WORKDIR usr/src/app
COPY packages*.json ./
RUN npm install
COPY . .
ENTRYPOINT [ "node" ]
CMD [ "app.js" ]