FROM debian:stretch
LABEL maintainer "admin@centos.bz"
RUN apt-get update && apt-get -y install shadowsocks && rm -rf /var/lib/apt/lists/*
ENTRYPOINT ["ssserver", "--fast-open"]
EXPOSE 8388