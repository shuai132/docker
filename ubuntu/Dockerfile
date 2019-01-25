FROM ubuntu:18.04

RUN apt update &&\
    apt install -y zsh htop ranger nmon curl wget git clang&&\
    chsh -s /bin/zsh

RUN echo `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

WORKDIR /data
CMD ["tail", "-f", "/dev/null"]
