FROM gogs/gogs

MAINTAINER bmsimang <bmsimang@student.wethinkcode.co.za>

RUN apk update

VOLUME /var/gogs /data

ENV USER=gogs

EXPOSE 22 3000

ENTRYPOINT ./gogs web

#docker run -it --rm --name=gogs -p 10022:22 -p 10080:3000
