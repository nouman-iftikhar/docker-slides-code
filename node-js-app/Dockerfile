FROM alpine
LABEL maintainer="noumansatti7@gmail.com"
RUN apk add --update nodejs npm
COPY . /src
WORKDIR /src
RUN npm install
ENV CREATEDBY="Nouman"
EXPOSE 8080
ENTRYPOINT ["node", "./app.js"]
