FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /todo-app
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "test" ]