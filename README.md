# zokrates.github.io

This repo hosts the ZoKrates documentation: [zokrates.github.io](https://zokrates.github.io)

# Contributing

The ZoKrates documentation is based on Markdown files which are located in the [main respository](https://github.com/Zokrates/ZoKrates/tree/develop/zokrates_book/src).
The utility [Mdbook](https://github.com/rust-lang-nursery/mdBook) renders these files to a static website that is currently manually pushed to this repository.

To build the mdbook, [install Rust], and then:

```bash
$ git clone https://github.com/Zokrates/ZoKrates
$ cd zokrates_book
$ cargo install mdbook
$ mdbook build
```
