FROM node:latest
RUN mkdir -p /app
WORKDIR /app
COPY package.json /app
RUN yarn install
COPY . /app
EXPOSE 8080
CMD ["yarn","serve"]