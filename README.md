# reading-log

Working copies of public domain prose I use as input when a parser has to cope
with real text instead of fixtures.

## Contents

- `book-01.txt` — 69 KB
- `book-02.txt` — 56 KB
- `book-03.txt` — 71 KB
- `book-04.txt` — 52 KB
- `book-05.txt` — 96 KB
- `book-06.txt` — 100 KB
- `book-07.txt` — 91 KB
- `book-08.txt` — 106 KB
- `book-09.txt` — 101 KB

## Why these

The Idiot (Fyodor Dostoevsky) is long enough to expose the bugs that short samples never
reach: inconsistent paragraph markers, dialogue dashes, long sentences and a
translator's spelling quirks. The Gutenberg text is public domain
(#2638), so it can sit in a repo without a licence question.

## Status

Nothing here is generated code. It is raw input, kept where my benchmarks can
find it. Split points follow paragraph breaks, not fixed byte counts, so the
files do not all start and end mid-sentence.

## TODO

- [ ] add a tokenizer that keeps the dialogue dashes
- [ ] measure paragraph length distribution
- [ ] compare two translations of the same chapter
