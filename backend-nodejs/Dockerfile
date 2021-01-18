FROM node:14.15.4-slim
RUN mkdir /app
COPY . /app
WORKDIR /app
RUN npm install
EXPOSE 3000
CMD ["node", "index.js"]