FROM node:20-alpine
WORKDIR /P3
COPY . .
RUN yarn install --production
EXPOSE 3000
CMD ["node", "src/index.js"]

