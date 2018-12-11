aw-server-rust
==============

A reimplementation of aw-server in Rust

Primary features missing:
- Config
- Import HTTP api
- Safe CORS (not allow all, fix dynamic CORS in rocket_cors upstream)

Caveats:
- Some refactoring is needed
- Lots of TODO and FIXME comments

Bugs:
- Memory leak during import? (wtf rust?)

Features missing compared to aw-server python:
- Swagger support

### How to compile

cargo build --release

### How to run

Install rust nightly and run

cargo run
