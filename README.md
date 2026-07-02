# Unreal Reels — A Practitioner's Guide to Turning Books into Video

An **AI+1** book: one human plus AI agents, making a book neither could make alone. This one
teaches the [Unreal Reels](https://github.com/nikbearbrown/unreal-reels) pipeline — how to turn
a written book (a chapter, a song, a topic) into finished short video: narrated lectures,
one-minute explainers, mini-biographies, and kids' language-learning music videos.

The thesis in one line: **audio is the master clock, the human signs every gate, and the
machine does everything in between.** Anchored to a real, fact-checked book, the pipeline
produces a *spine* — a high-quality, accurate starting point an expert refines into something
their own — instead of the generic slop a single prompt returns.

## Read it

The book is in [`chapters/`](chapters/), twelve chapters in three parts:

**Foundations** — the two laws · the beat sheet · storyboard-first
**Making videos** — Songbird (music, lyric, dance, kids' language videos) · Bios · Explainer · Chapter → Lecture
**Scale & trust** — silent mode · fidelity & the fact commons · the look · the ecosystem · making it yours

Every chapter opens with *why* the pipeline works the way it does, then gives exercises that
each end in an artifact you made.

## Build it

This repository follows the [AI+1](https://github.com/nikbearbrown) book structure. Planning
artifacts (`vision.md`, `architecture.md`, `chapters-spec.md`, `outline.md`, `risks.md`) sit at
the root; `metadata.yaml` drives the build. To produce EPUB/HTML with the AI+1 tooling:

```bash
bash build.sh     # pandoc → output/unreal-reels-book.epub + .html
```

## Companion systems

- **[Unreal Reels](https://github.com/nikbearbrown/unreal-reels)** — the video pipeline this book documents.
- **AI+1 (`ai1-cli`)** — the book-generation system this book was made with.

## License

Text © 2026 Nik Bear Brown / Bear Brown, LLC. The Unreal Reels pipeline itself is released
separately under the MIT License.
