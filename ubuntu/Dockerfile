FROM ubuntu:18.04

RUN apt update &&\
    apt install -y zsh htop ranger nmon curl wget git clang&&\
    chsh -s /bin/zsh

RUN apt install -y cmake make gcc g++

RUN sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

WORKDIR /host
CMD ["tail", "-f", "/dev/null"]
