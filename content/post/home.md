+++
title = 'Essentialist'
date = 2024-09-21T23:33:46+01:00
+++


Programs for [spaced repetition][1] using flashcards in [Markdown][2].

- **Essentialist**: Application for desktops and mobiles
- **Flashdown**: Console application

The space repetition algorithm used is based on [SM-2][3].

Key features:

- **Privacy**: No cloud, your data never leave your device.
- **Easy card creation**: Flash cards are plain text Markdown files.
- **Cross-platform**: Runs on Linux, MacOS, Windows and android.

[1]: https://en.wikipedia.org/wiki/Spaced_repetition
[2]: https://en.wikipedia.org/wiki/Markdown
[3]: https://en.wikipedia.org/wiki/SuperMemo#Description_of_SM-2_algorithm

See the [CONTRIBUTING.md](/.github/CONTRIBUTING.md) for how to report bugs and
submit pull request.

## Flash cards syntax

Each deck of cards is a plain text Markdown files with the extension `.md` (ex:
`sample.md`). You can put all your decks in the same directory.

Each card starts with a heading level 2 (line starting with `##`) defining the
question. The answer is the content following (until the next heading level 2).

You progress is stored in a hidden file `.<deck file>.db` (ex: `.sample.md.db`).

Example of a deck with 3 cards:

```markdown
## Question: what format is used?

Questions and answers are in **Markdown**.

## Are lists supported?

Yes, here is an example:

- one
- **two**
- three

## How to include a table in the answer?

Answer with a table.

|  A  |  B  |
| --- | --- |
| 124 | 456 |
```

## Essentialist

A GUI version for desktops and mobile (Android, iOS support isn't tested).

## Flashdown (terminal version)

Flashdown is the terminal application.
