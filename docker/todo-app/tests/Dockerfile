FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app/test

ADD node_modules.tar.gz ./  

COPY ./ ./

# COPY jest.config.js ./
# COPY ./e2e ./e2e/
# COPY package.json ./

CMD [ "npm", "test" ]