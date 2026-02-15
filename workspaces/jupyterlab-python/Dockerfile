FROM prairielearn/workspace-jupyterlab-base:latest
ARG CACHEBUST=2026-02-15-14-13-06

USER root
COPY install.sh requirements.txt /
RUN /bin/bash /install.sh

USER jovyan
