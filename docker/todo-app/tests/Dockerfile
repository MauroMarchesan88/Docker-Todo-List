FROM mjgargani/puppeteer:trybe1.0 as todotests
WORKDIR /app
ADD node_modules.tar.gz /app
COPY . .
EXPOSE 3000
CMD ["npm", "test"]
