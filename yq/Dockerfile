FROM alpine:latest

RUN wget https://github.com/mikefarah/yq/releases/download/2.4.0/yq_linux_amd64 -O /usr/bin/yq && \
    chmod +x /usr/bin/yq

ENTRYPOINT ["/usr/bin/yq"]