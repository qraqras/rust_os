FROM rust:1.87.0
RUN apt update && apt install -y \
    git \
    qemu-system-x86 \
    xxd \
    build-essential \
    netcat-openbsd \
 && rustup component add \
    rustfmt \
    clippy \
 && rustup target add x86_64-unknown-uefi
