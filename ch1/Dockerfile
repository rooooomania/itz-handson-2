FROM node:10

COPY package.json /src/package.json
RUN cd /src; npm install --production

COPY . /src

EXPOSE 8080
CMD ["node", "/src/index.js"]


