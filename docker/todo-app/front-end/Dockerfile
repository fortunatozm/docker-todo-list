FROM node:14-alpine
#RUN npm i -g create-react-app
#RUN create-react-app 01container
WORKDIR /
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]
