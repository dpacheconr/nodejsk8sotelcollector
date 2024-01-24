FROM node
RUN mkdir -p /opt/app
WORKDIR /opt/app
COPY . .
RUN npm install
EXPOSE 8080
CMD [ "node", "--require", "./src/instrumentation.js" , "./src/app.js"]