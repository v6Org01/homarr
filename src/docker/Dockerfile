ARG REGISTRY
ARG REPO
ARG TAG
FROM ${REGISTRY}/${REPO}:${TAG}
LABEL maintainer="dev_lau11@a.jlv6.com"
LABEL os="alpine"
RUN PUID=1000 PGID=2000 /app/entrypoint.sh
RUN chown -R 1000:2000 /appdata
USER 1000:2000
ENTRYPOINT []
CMD ["/bin/sh", "run.sh"]
