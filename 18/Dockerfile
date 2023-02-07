FROM node:18-alpine3.17

RUN apk add curl python3 && \
  apk add py3-pip && \
  apk add --no-cache libc6-compat && \
  npm install pm2 -g && pm2 install pm2-logrotate

CMD ["node"]