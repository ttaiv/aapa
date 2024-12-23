# Running the program

Assuming that you have [Rust and Cargo](https://www.rust-lang.org/learn/get-started) installed and you are in the project root:

Build and run the development version

```bash
cargo run
```

Build the final program

```bash
cargo build --release
```

Run it

```bash
./target/release/aapa
```

Add it to your system's path to do the silly printing whenever you feel like it (these exact commands should work on Linux and Mac)

```bash
# Create directory for the program if it does not exist.
mkdir -p ~/.local/bin
# Copy the executable there.
cp target/release/aapa ~/.local/bin
```

You can use any directory that is in your system's `PATH`. The example used `~/.local/bin`.
