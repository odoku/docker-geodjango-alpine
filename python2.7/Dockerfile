FROM odoku/geopython:2.7

RUN echo "http://dl-cdn.alpinelinux.org/alpine/edge/main" >> /etc/apk/repositories \
    && apk add --update \
      tzdata \
      py-psycopg2 \
    && pip install --no-cache-dir \
      django \
    && rm -rf /var/cache/apk/*
