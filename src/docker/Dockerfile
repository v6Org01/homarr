ARG REGISTRY=ghcr.io
ARG REPO=homarr-labs/homarr
ARG TAG=v1.45.2
FROM ${REGISTRY}/${REPO}:${TAG}
LABEL maintainer="dev_lau11@a.jlv6.com"
RUN PUID=20009 PGID=20009 /app/entrypoint.sh
RUN chown -R 20009:20009 /appdata
USER 20009:20009
ENTRYPOINT []
CMD ["/bin/sh", "run.sh"]
