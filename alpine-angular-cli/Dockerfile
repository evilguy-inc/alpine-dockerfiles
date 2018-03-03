FROM evilguy/node:0.1


RUN apk add --update python


RUN mkdir -p /usr/lib/node_modules \
  && chmod g+s  /usr/lib/node_modules \
  && npm install -g @angular/cli --unsafe-perm --ensure \
  && rm -rf /var/cache/apk/*

