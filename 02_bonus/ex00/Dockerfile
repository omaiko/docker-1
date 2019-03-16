FROM debian

RUN apt-get update && apt-get install -y cowsay fortune lolcat

ENTRYPOINT /usr/games/fortune | /usr/games/cowsay -f stegosaurus | /usr/games/lolcat
# `docker build -t ex00 .`
# `docker run --rm -t ex00`
# https://ru.wikipedia.org/wiki/Cowsay - list of "cows"
