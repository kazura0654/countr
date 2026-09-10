# countr

Fast line/byte counter written in Rust

## Installation

```bash
cargo build --release
```

## What it does

- Reads stdin or multiple files
- Zero dependencies outside std
- Counts lines, words and bytes like wc
- Parallel over files with std threads

## Examples

```bash
./target/release/countr src/*.rs
cat README.md | ./target/release/countr
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── main.rs
├── .gitignore
├── CONTRIBUTING.md
├── Cargo.toml
└── SECURITY.md
```
