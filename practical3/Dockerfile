FROM node:20-alpine
WORKDIR /P3
COPY . .
RUN YARN install --production
EXPOSE 80
CMD ["node", "src/index.js"]