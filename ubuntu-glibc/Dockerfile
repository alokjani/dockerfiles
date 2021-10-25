FROM ubuntu:20.04

RUN set -x \
 && export DEBIAN_FRONTEND=noninteractive \
 && sudo apt-get update \
 && sudo apt-get install -y \
        bison \
        gawk \
        gettext \
        openssl \
        python3 \
        texinfo \
        wget \
# Cleanup apt cache
 && sudo apt-get clean

