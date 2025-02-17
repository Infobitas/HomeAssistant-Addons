ARG BUILD_FROM
FROM $BUILD_FROM

RUN apk add --no-cache \
        mpc \
        mpd \


ENTRYPOINT [ "/init" ]
CMD []
COPY root /
