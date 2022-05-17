
FROM node:14-alpine AS todofrontend
WORKDIR /app
ADD node_modules.tar.gz /app
ADD .env /app
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
