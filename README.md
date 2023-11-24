## wry-test

A Simple Test Rig for Exposing GTK-Webkits slow startup times.

Tests can be run by compiling the project in release mode and simply using
`time` or `hyperfine`:

```bash
$ cargo build --release
$ time ./target/release/wry-test
$ hyperfine ./target/release/wry-test
```
