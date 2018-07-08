# Don't edit this file, user DockerfileTemplate and buildImage.sh
###############################################
FROM registry.services.alin.be/rabbitmq:3.7-alpine
COPY localtime /etc/localtime
RUN apk add --no-cache bash
COPY docker-healthcheck /usr/local/bin/
#HEALTHCHECK CMD ["docker-healthcheck"]
