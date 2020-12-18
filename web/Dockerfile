from node:10-alpine
WORKDIR web
COPY . .
RUN apk add --no-cache ca-certificates \
    && apk update \
    && npm install
expose 8083