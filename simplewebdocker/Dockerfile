FROM node:14-alpine

WORKDIR /usr/app

COPY ./package.json ./

RUN npm install

COPY ./ ./

CMD [ "npm", "start" ]

# command 1 -> docker build --no-cache --progress=plain -t vivek/simpleweb .
# command 2 -> docker run -p 8080:8080 vivek/simpleweb
# -p is used for port forwarding
