FROM mjgargani/puppeteer:trybe1.0

ADD node_modules.tar.gz /tests
COPY ./e2e /tests
COPY jest.config.js /tests
COPY package.json /tests
COPY package-lock.json /tests

CMD [ "npm", "test" ]
