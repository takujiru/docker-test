FROM debian:wheezy

MAINTAINER takuya higurashi <takujiru6242@gmail.com>
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]
