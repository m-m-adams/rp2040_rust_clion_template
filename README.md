# Starter template for EE499

Setup:
1. Install probe-rs `cargo install probe-rs-tools`
2. Install the board target `rustup target add thumbv6m-none-eabi`
3. `cargo run` will flash and run the program
4. `cargo embed` will flash and run the program with GDB. To use GDB in RustRover you need to download at least version 2025.2, otherwise you can use it from the terminal or in CLion with the Rust plugin
