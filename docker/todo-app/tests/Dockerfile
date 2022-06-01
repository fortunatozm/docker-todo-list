FROM mjgargani/puppeteer:trybe1.0
#RUN npm i -g create-react-app
#RUN create-react-app 01container
WORKDIR /
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "test"]
