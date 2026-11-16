PID   USER     TIME  COMMAND
    1 root      0:00 node src/index.js
   18 root      0:00 ps aux
dc728e061d70
NAME="Alpine Linux"
ID=alpine
VERSION_ID=3.24.4
PRETTY_NAME="Alpine Linux v3.24"
HOME_URL="https://alpinelinux.org/"
BUG_REPORT_URL="https://gitlab.alpinelinux.org/alpine/aports/-/issues"
639
x | grep "node src/index.js"
  639 root      0:00 node src/index.js
template parsing error: template: :1:18: executing "" at <.NetworkSettings.IPAddress>: map has no entry for key "IPAddress"
IMAGE          CREATED          CREATED BY                                      SIZE      COMMENT
18918a2230e4   9 minutes ago    CMD ["node" "src/index.js"]                     0B        buildkit.dockerfile.v0
<missing>      9 minutes ago    EXPOSE [3000/tcp]                               0B        buildkit.dockerfile.v0
<missing>      9 minutes ago    RUN /bin/sh -c yarn install --production # b…   59.5MB    buildkit.dockerfile.v0
<missing>      10 minutes ago   COPY . . # buildkit                             4.73MB    buildkit.dockerfile.v0
<missing>      10 minutes ago   WORKDIR /app                                    8.19kB    buildkit.dockerfile.v0
<missing>      4 days ago       CMD ["node"]                                    0B        buildkit.dockerfile.v0
<missing>      4 days ago       ENTRYPOINT ["docker-entrypoint.sh"]             0B        buildkit.dockerfile.v0
<missing>      4 days ago       COPY docker-entrypoint.sh /usr/local/bin/ # …   20.5kB    buildkit.dockerfile.v0
<missing>      4 days ago       RUN /bin/sh -c apk add --no-cache --virtual …   5.48MB    buildkit.dockerfile.v0
<missing>      4 days ago       ENV YARN_VERSION=1.22.22                        0B        buildkit.dockerfile.v0
<missing>      4 days ago       RUN /bin/sh -c addgroup -g 1000 node     && …   163MB     buildkit.dockerfile.v0
<missing>      4 days ago       ENV NODE_VERSION=22.23.5                        0B        buildkit.dockerfile.v0
<missing>      10 days ago      CMD ["/bin/sh"]                                 0B        buildkit.dockerfile.v0
<missing>      10 days ago      ADD alpine-minirootfs-3.24.4-x86_64.tar.gz /…   9.09MB    buildkit.dockerfile.v0
