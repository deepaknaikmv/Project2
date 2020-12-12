FROM node:current-slim
WORKDIR /src/app
COPY package.json /src/app
COPY . /app
RUN npm install
EXPOSE 3000
CMD ["node","dev"]