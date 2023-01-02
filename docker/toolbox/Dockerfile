FROM alpine
RUN apk add --no-cache curl wget busybox-extras make netcat-openbsd zsh tree python3 vim py-pip bash && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
