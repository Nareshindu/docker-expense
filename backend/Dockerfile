FROM node:20
ENV DB_HOST="naidu1"
EXPOSE 8080
RUN mkdir /app
WORKDIR /app
COPY *.json /app
COPY *.js /app
RUN npm install
CMD [ "node", "index.js" ]