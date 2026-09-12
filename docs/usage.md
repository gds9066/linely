# Usage

The README covers the basics. This page collects the
longer examples and the notes that did not fit up front.

## Basic

```bash
./target/release/linely src/*.rs
cat README.md | ./target/release/linely
```

## Notes

- Counts lines, words and bytes like wc
- Parallel over files with std threads
