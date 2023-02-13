FROM alpine:3.17.2
ARG ARCH
ENV ARCH=$ARCH
COPY bin/fleetcontroller-linux-${ARCH} /usr/bin/fleetcontroller
USER 1000
CMD ["fleetcontroller"]
