ARG BASE=ghcr.io/linuxserver/bookstack:latest
FROM ${BASE}

# Pick up Alpine's fixed PHP packages ahead of LinuxServer's next rebuild
RUN apk upgrade --no-cache
