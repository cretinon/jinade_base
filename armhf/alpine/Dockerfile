FROM scratch
ADD data/rootfs.tar /
ADD data/qemu-arm-static /usr/bin/qemu-arm-static
RUN apk add --no-cache --purge -uU bash && \
    rm -rf /var/cache/apk/* /tmp/*
