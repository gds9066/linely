# linely

Learning Rust by rewriting coreutils, one tool at a time

Side project, maintained when I have time.

## Usage

```bash
./target/release/linely src/*.rs
cat README.md | ./target/release/linely
```

## Installation

```bash
cargo build --release
```

## What it does

- Counts lines, words and bytes like wc
- Parallel over files with std threads
- Zero dependencies outside std
- Reads stdin or multiple files

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── main.rs
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── Cargo.toml
└── LICENSE
```

## Development

```bash
cargo build
cargo clippy -- -D warnings
```

## License

MIT - see [LICENSE](LICENSE).
