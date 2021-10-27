FROM ubuntu:20.04

RUN set -x \
 && export DEBIAN_FRONTEND=noninteractive \
 && apt-get update \
 && apt-get install -y \
        bison \
        gawk \
        gettext \
        openssl \
        python3 \
        texinfo \
        wget \
# Cleanup apt cache
 && apt-get clean

