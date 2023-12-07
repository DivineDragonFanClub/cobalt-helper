# Tauri + Leptos

This template should help get you started developing with Tauri and Leptos.

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer).

# Pre-requisites

Do note, you may be asked to give executables networking permissions in the process, this will be a dialogue.
```bash
# install tauri-cli
cargo install tauri-cli

# install wasm stuff for leptos
cargo install trunk
rustup target add wasm32-unknown-unknown

# optionally
rustup update
```
Tip: If you hate compiling you can use `binstall` instead of `install` via [cargo-binstall](https://github.com/cargo-bins/cargo-binstall). 
```bash
# run
cargo tauri run

# build
cargo tauri build
```
Small anecdote (Sohn), command failed inside the windows-terminal oddly enough, however, it did work in vscode + rustanalyzer lmao.