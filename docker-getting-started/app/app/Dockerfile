FROM node:12-alpine
RUN apk add --no-cache python 
RUN apk add g++ 
RUN apk add make
WORKDIR /app
COPY . .
RUN yarn install --production
CMD ["node", "src/index.js"]