ARG BUILD_FROM
FROM $BUILD_FROM

FROM ghcr.io/hassio-addons/base:latest

RUN apk add --no-cache \
        mpc=0.35-r0 \
        mpd-0.23.16-r0


ENTRYPOINT [ "/init" ]
CMD []
COPY root /
