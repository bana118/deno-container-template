FROM denoland/deno:debian

RUN apt update \
    && apt install -y --no-install-recommends \
    apt-utils \
    ca-certificates \
    git \
    && apt autoremove -y \
    && apt clean -y \
    && rm -rf /var/lib/apt/lists/*
