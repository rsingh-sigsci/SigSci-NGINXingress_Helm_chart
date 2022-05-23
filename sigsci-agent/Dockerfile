FROM alpine:latest

RUN apk add --no-cache curl
RUN curl https://dl.signalsciences.net/sigsci-agent/sigsci-agent_latest.tar.gz | tar -xf - -C /usr/sbin/

ENTRYPOINT ["/usr/sbin/sigsci-agent"]
