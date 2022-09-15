FROM node:18-alpine3.15

RUN npm install -g http-server
WORKDIR ./app
ADD ./dist ./dist

RUN ls -la

EXPOSE 8080
CMD  [ "http-server", "dist" ]

