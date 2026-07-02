# Chapters spec — Unreal Reels: A Practitioner's Guide

Per-chapter contract. Each chapter: overview (why it works this way) → 4–6 content blocks → one worked example → 3+ exercises at Apply or above, each ending in an artifact.

---

**Ch 1 — The Two Laws.** *Capability:* explain why audio-as-master-clock and phase-gating make quality controllable. *Blocks:* the master-clock rule; the gate discipline; regenerate-only-the-failing-unit; slop vs. spine. *Worked ex:* trace how swapping one audio clip re-times a whole reel. *Exercises:* find the gate in a described failure; justify a gate you'd refuse.

**Ch 2 — The Beat Sheet.** *Capability:* read/edit `beat_sheet.json`. *Blocks:* one beat = one narrated unit = one visual; the fields (`beat_id`, `narration_text`, `actual_duration_s`, `visual_mode`…); why one schema composes; measured vs. estimated duration. *Worked ex:* add a beat and re-derive timing. *Exercises:* hand-edit a beat; spot an unfilled narration slot.

**Ch 3 — Storyboard-First.** *Capability:* run the reels engine to a first still set. *Blocks:* segment → audio → references → stills → video → overlay; the reference library; curate at each gate; the committed definition vs. regenerable output. *Worked ex:* segment a short story, generate audio, read durations. *Exercises:* generate references and pick keepers; regenerate one weak still.

**Ch 4 — Songbird.** *Capability:* produce a music/lyric/dance video, incl. kids' language-learning music videos. *Blocks:* muzak beat grid; `lyric-match` (one lyric line = one clip); `songbird-dance` (Seedance, long downbeat beats); forced-aligned lyrics. *Worked ex:* align a short lyric to its audio. *Exercises:* build a lyric-matched reel; make a kids' vocab music video.

**Ch 5 — Bios.** *Capability:* produce a mini-biography. *Blocks:* one figure, one life; narration over B-roll; reference plates for a real person; photograph vs. redraw ethics. *Worked ex:* segment a life into beats. *Exercises:* build a 60-second mini-bio; swap the closing beat.

**Ch 6 — Explainer.** *Capability:* produce a sketch explainer. *Blocks:* MinutePhysics progressive disclosure; `bears-doodles` (one narration line = one drawn element); scout a book for candidates (FIELD); Manim vs. Remotion doodles. *Worked ex:* storyboard one concept. *Exercises:* scout a chapter; build one explainer.

**Ch 7 — From Chapter to Lecture.** *Capability:* chapter → narrated lecture. *Blocks:* the three stages (`lecture-assets` → `slide-deck` → `deck-lecture`); the plan gate; discuss-don't-read; the visual tiers. *Worked ex:* run the plan and read it. *Exercises:* build a deck from a chapter; narrate and preview one lecture in Studio.

**Ch 8 — Silent Mode.** *Capability:* rough drafts at scale. *Blocks:* attention is the bottleneck; the triage layer (QC score, decision log, contact sheet, preview); the three modes; regenerate-only-the-failing-unit at fleet scale. *Worked ex:* run `silent_run.py` on one chapter and read `STATUS.md`. *Exercises:* run several; sort a fleet manifest worst-first.

**Ch 9 — Fidelity.** *Capability:* judge accuracy. *Blocks:* fidelity vs. watchability; Tier A (grounded in the chapter) and Tier B (the fact commons); flags as a triage list; corrections write back as signed evidence. *Worked ex:* read a `grounding.json` flag. *Exercises:* run the grounding check; adjudicate one flag.

**Ch 10 — The Look.** *Capability:* apply the design system. *Blocks:* one red, ink, grays, no blue; typography; progressive disclosure; no static screen > ~5s. *Worked ex:* diagnose a wall-of-text slide. *Exercises:* fix a static-screen violation; re-tier a slide.

**Ch 11 — The Ecosystem.** *Capability:* trace the whole factory. *Blocks:* AI+1 writes the book; `facts/` is the shared truth; Unreal Reels makes the video; verified-artifact gates and `sync-to-book.sh`. *Worked ex:* trace one claim book→commons→video. *Exercises:* sign a lecture gate; explain what your signature warrants.

**Ch 12 — Making It Yours.** *Capability:* refine and ship. *Blocks:* the spine as a starting point; conversational refinement; voices; two experts diverge from one base. *Worked ex:* rewrite one beat conversationally and re-render. *Exercises:* re-voice a lecture; ship a final cut.
