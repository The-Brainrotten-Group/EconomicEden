FROM rust:1.77

WORKDIR /usr/src/backend
COPY . .

RUN cargo install --path .

CMD ["api"]
