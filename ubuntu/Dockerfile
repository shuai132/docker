FROM python:3.7

RUN apt update &&\
    apt install -y zsh htop ranger nmon &&\
    chsh -s /bin/zsh

RUN echo `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

WORKDIR /data
CMD ["tail", "-f", "/dev/null"]
