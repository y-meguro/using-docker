FROM debian/eol:wheezy

LABEL maintainer = "y.meguro.2008@gmail.com"
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/usr/games/cowsay"]
