FROM ubuntu:bionic

RUN apt-get -qq update && \
    apt-get -y install pbuilder aptitude build-essential clang llvm git libelf-dev zlibc vim-common pkg-config xxd

COPY . /srv/

WORKDIR /srv

