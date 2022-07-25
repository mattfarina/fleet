FROM alpine:3.16.1
ARG ARCH
ENV ARCH=$ARCH
COPY bin/fleetcontroller-linux-${ARCH} /usr/bin/fleetcontroller
USER 1000
CMD ["fleetcontroller"]
