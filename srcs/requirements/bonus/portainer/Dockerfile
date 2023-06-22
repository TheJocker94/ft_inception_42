FROM alpine:3.17

FROM portainer/portainer-ce:latest

VOLUME /var/run/docker.sock:/var/run/docker.sock
VOLUME /data

EXPOSE 8000
EXPOSE 9443

ENTRYPOINT ["/portainer"]
CMD ["--bind", "0.0.0.0", "--data", "/data"]