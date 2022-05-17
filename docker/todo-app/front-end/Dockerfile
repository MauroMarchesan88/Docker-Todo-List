FROM node:14-alpine AS todofrontend
WORKDIR /app
ADD node_modules.tar.gz /app
COPY . .
ADD .env /app
EXPOSE 3000
CMD ["npm", "start"]
