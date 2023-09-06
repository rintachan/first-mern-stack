FROM node:alpine
#FROM node:alpine AS build
WORKDIR /app
COPY package*.json .
RUN npm install
#RUN npm install react-router-dom
COPY . .
EXPOSE 3000
CMD [ "npm", "start" ]
#RUN npm run build

#FROM nginx
#COPY --from=build /app/build /usr/share/nginx/html