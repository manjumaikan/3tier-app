from node:10-alpine
WORKDIR api
COPY . .
RUN apk add --no-cache ca-certificates \
    && apk update \
    && npm install
expose 8082