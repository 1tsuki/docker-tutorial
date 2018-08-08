FROM debian:wheezy

MAINTAINER Itsuki Sakitsu <itsuki.sakitsu@gmail.com>
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]
