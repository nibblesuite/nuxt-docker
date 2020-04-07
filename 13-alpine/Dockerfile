FROM node:13-alpine
WORKDIR /app
RUN apk add python make g++ && npm i -g nuxt
COPY docker-entrypoint.sh /usr/local/bin/
ENTRYPOINT ["docker-entrypoint.sh"]
CMD [""]