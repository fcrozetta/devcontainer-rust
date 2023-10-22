FROM debian:latest
LABEL org.opencontainers.image.description FCrozetta simple rust Image for devcontainer

RUN apt update
RUN apt install build-essential -y
RUN apt install curl -y
RUN curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf > install-rust.sh
RUN bash ./install-rust.sh -y
