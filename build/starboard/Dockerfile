FROM alpine:3.21

RUN adduser -u 10000 -D -g '' starboard starboard

COPY starboard /usr/local/bin/starboard

USER starboard

ENTRYPOINT ["starboard"]
