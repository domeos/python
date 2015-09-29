FROM alpine:3.2

MAINTAINER domeos

RUN apk add -U curl python3 && \
    curl -sSL https://bootstrap.pypa.io/get-pip.py | python3 && \
    pip install virtualenv && \
    rm -rf /var/cache/apk/*

CMD ["python3"]

