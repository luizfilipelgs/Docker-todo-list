
FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /todo-app/tests/e2e

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT ["npm", "test]
