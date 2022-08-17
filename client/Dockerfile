FROM node:10
WORKDIR /opt/app
COPY package*.json ./
COPY . .
RUN CI=true
RUN npm install
EXPOSE 8000
CMD [ "npm", "start" ]