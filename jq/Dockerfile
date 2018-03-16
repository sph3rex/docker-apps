FROM alpine

RUN apk add \
    --update \
    --no-cache \
        curl \
        jq

ENTRYPOINT ["jq"]
CMD ["--help"]