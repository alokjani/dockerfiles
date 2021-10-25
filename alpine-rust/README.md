# Rust Docker Image

Rust Image with Alpine.

## Usage

    $ echo -e 'fn main() { println!("Hello Docker"); }' > qq.rs
    $ docker run --rm -v "$(pwd):/tmp" --workdir /tmp alokjani/alpine-rust rustc -C target-feature=+crt-static ./qq.rs
