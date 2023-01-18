FROM node:14-alpine

EXPOSE 3001

ADD node_modules.tar.gz /back-end
COPY package.json /back-end
COPY package-lock.json /back-end
COPY ./src /back-end

CMD [ "npm", "start" ]
