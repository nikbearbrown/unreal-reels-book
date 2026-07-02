# BLUEPRINT.md — Unreal Reels: A Practitioner's Guide to Turning Books into Video

**Author:** Nik Bear Brown
**Status:** Synthesized from planning files + chapters in silent mode (Blueprint /scaffold). Review before use.

---

## Concept
A finished book is raw material for a dozen other forms. Unreal Reels is the phase-gated pipeline that makes videos — narrated lectures, explainers, mini-bios, music videos — from books, and this book teaches you to run it. The thesis in one line: audio is the master clock, the human signs every gate, and the machine does everything in between.

**Target course / reader:** A practitioner — teacher, author, or course-builder — who already has written material (their own, or an AI+1 book) and wants video from it. Comfortable talking to a CLI agent (Cowork, Claude Code, Codex) and pasting commands the agent hands them, but not necessarily a programmer. Cares above all that the video is accurate and quickly becomes theirs. Problem-first, whole-task: every chapter ends with an artifact they made.

## Three-Act Arc
From architecture.md / outline.md:
- **Act I — Foundations (Ch 1–3):** the two laws, the beat sheet, the storyboard engine. The reader learns the invariants before any genre.
- **Act II — Making videos (Ch 4–7):** the three reels aspects plus the lecture pipeline. The reader makes one of each.
- **Act III — Scale & trust (Ch 8–12):** silent mode, fidelity, the look, the ecosystem, and refinement. The reader goes from one video to a whole book's worth, and learns what only they can decide.

## Chapter-by-Chapter
| # | Chapter | Capability built (DO) |
|---|---------|----------------------|
| Intro | Introduction | Explain what Unreal Reels is, the two laws, and the three ways in; know how to read the book. |
| 1 | The Two Laws | Explain why audio-as-master-clock and phase-gating make quality controllable, and identify a broken gate in a described failure. |
| 2 | The Beat Sheet | Read and hand-edit a `beat_sheet.json` — add a beat, re-derive timing, spot an unfilled narration slot. |
| 3 | Storyboard-First | Run the reels engine (segment → audio → references → stills → video → overlay) to a first still set and pick keepers. |
| 4 | Songbird | Produce a music/lyric/dance video, including a kids' language-learning music video. |
| 5 | Bios | Produce a narrated mini-biography over B-roll — one figure, one life. |
| 6 | Explainer | Produce a MinutePhysics-style sketch explainer with `bears-doodles` and scout a chapter for candidates. |
| 7 | From Chapter to Lecture | Turn a chapter into a narrated lecture across all three stages (`lecture-assets` → `slide-deck` → `deck-lecture`). |
| 8 | Silent Mode | Run silent mode over several chapters at scale and read the triage manifest worst-first. |
| 9 | Fidelity | Run the grounding check and judge a fidelity flag against a fact-checked book. |
| 10 | The Look | Apply the brutalist design system and fix a static-screen violation. |
| 11 | The Ecosystem | Trace one claim from book → fact commons → video and sign a lecture gate. |
| 12 | Making It Yours | Refine a lecture into your own voice and ship a final cut. |

*All 12 chapters are drafted. Chapter H1 titles confirmed against outline.md.*

## Prerequisites
From vision.md / architecture.md: the reader can talk to a CLI agent (Cowork, Claude Code, Codex) and paste commands the agent hands them; not necessarily a programmer. They already have written material to turn into video (ideally a fact-checked AI+1 book, since fidelity is by construction downstream of one). Foundations before genres, genres before scale: a reader who tries silent mode (Ch 8) without the beat sheet (Ch 2) will not understand why swapping audio re-times everything for free.

## Positioning (one line)
The practitioner's manual for the Unreal Reels video pipeline — a companion to the AI+1 book-generation system: where AI+1 teaches you to make a book, this teaches you to make accurate, ownable video *from* that book, via an audited pipeline rather than a single prompt.
