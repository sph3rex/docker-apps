FROM node:8.9.4-alpine

RUN apk add --no-cache \
    python3 \
    py-pip \
    ca-certificates \
    groff \
    less \
    bash

RUN yarn global add serverless@1.25.0

ENTRYPOINT ["sls"]