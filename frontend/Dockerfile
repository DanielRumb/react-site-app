FROM node:alpine as builder
WORKDIR  '/react-site-app/frontend'

COPY package.json package-lock.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "start"]