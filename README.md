## wry-test

A Simple Test Rig for Exposing GTK-Webkits slow startup times.

The script is designed to let the window just barely render on screen with a
predicable time wait before exiting the program.

Tests can be run by compiling the project in release mode and simply using
`time` or `hyperfine`:

```bash
$ cargo build --release
$ time ./target/release/wry-test
$ hyperfine ./target/release/wry-test
```
