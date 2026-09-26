---
name: short-form-video-script-writer
description: Write scroll-stopping short-form video scripts for TikTok, Instagram Reels, and YouTube Shorts (15-60s). Generates a hook, value beats, on-screen text overlays, a shot-by-shot storyboard, and a CTA — ready to film or hand to an editor. Use when a creator has a topic, niche, or hook and needs the actual script, not just an idea.
license: see LICENSE.txt
---

# Short-Form Video Script Writer

Turn a topic, niche, or hook into a finished, film-ready short-form script (15–60 seconds) for TikTok, Instagram Reels, and YouTube Shorts. The output is a complete script with timestamps, spoken lines, on-screen text overlays, a shot-by-shot storyboard, and a call-to-action — the piece your 4-step funnel (niche → hook → validate → convert) is missing.

> Adapted from `nicepkg/ai-workflow` `video-script-writer` (MIT License). Re-focused on short-form and extended with a storyboard + platform pacing layer.

## When to use

- "Write a 30-second TikTok hook script about [topic]."
- "I have a niche and a hook — give me the actual script."
- "Make a Reels script that opens with a pattern interrupt and ends with a save/comment CTA."
- "Turn this outline into a YouTube Shorts script with a storyboard."
- "Adapt my long video into a 45s Shorts version."

Do **not** use for: long-form YouTube essays, blogs, or ad copy (those are different structures — flag and offer the long-form variant instead).

## Inputs it needs (ask once, then proceed)

Collect only what's missing; never block on trivia:
- **Topic / hook** (required)
- **Platform**: TikTok / Reels / Shorts (default TikTok)
- **Length**: 15 / 30 / 45 / 60 seconds (default 30)
- **Goal**: educate / entertain / inspire / sell (default entertain)
- **Tone**: energetic / calm / witty / authoritative (default energetic)
- **CTA type**: follow / save / comment / link (default "follow + comment")

## Core structure (short-form, 15–60s)

```
SHORT-FORM SCRIPT — [Title]
Platform: [TikTok/Reels/Shorts]   Length: [N]s   Goal: [X]   Tone: [Y]
─────────────────────────────────────────────────────────────
🎯 HOOK (0–3s) — CRITICAL
   [Pattern interrupt / curiosity gap / bold claim]
   A: "Stop [doing X], do this instead…"
   B: "The [thing] nobody talks about…"
   C: "POV: you just discovered…"
   D: "[Shocking statement]"

📍 CONTEXT (3–8s)
   [Quick setup — who/what/why; one line]

💡 VALUE (8–N−10s)  — 1 beat per 8–12s, each with visual
   Beat 1: [point]  →  VISUAL: [what's on screen]
   Beat 2: [point]  →  VISUAL: [what's on screen]
   Beat 3: [point]  →  VISUAL: [what's on screen]

🔥 PAYOFF (N−10–N−5s)
   [Deliver on the hook promise; the "so what"]

📣 CTA (last 5s)
   "Follow for more [topic]" / "Save this for later" / "Comment [X] for part 2"

TEXT OVERLAYS (captions are essential):
   0:00  "[Hook text — large, centered]"
   0:03  "[Context]"
   …      [one per beat]

AUDIO NOTE:
   Trending sound? [Yes/No]   Voiceover style: [Energetic/Calm/ASMR]
─────────────────────────────────────────────────────────────
```

## Storyboard (shot-by-shot, fill the funnel gap)

Append a storyboard so the creator can film or brief an editor without guessing:

```
STORYBOARD
| # | Time   | Shot / Visual                    | Spoken line (VO)            | On-screen text     | Transition |
|---|--------|---------------------------------|-----------------------------|--------------------|------------|
| 1 | 0:00   | Face cam, lean-in, eyebrow raise | "Stop scrolling—"           | "STOP SCROLLING"   | hard cut   |
| 2 | 0:03   | B-roll of [X]                    | "this is why your…"         | "WHY YOUR ___"     | whip pan   |
| 3 | 0:08   | Screen recording / demo          | "Step one, you…"            | "STEP 1"           | zoom       |
…
```

## Hook formulas (pick by goal)

| Goal | Formula | Example |
|------|---------|---------|
| Curiosity | "What if I told you…" | "What if I told you your hook is killing your reach?" |
| Stakes | "This could change…" | "This could change how you script Reels forever." |
| Contrast | "Everyone thinks X, but…" | "Everyone thinks long videos win—but shorts do." |
| Question | "Have you ever…" | "Have you ever filmed 10 takes and quit?" |
| Bold claim | "The biggest [thing] since…" | "The biggest scripting mistake since 2020." |

## Pacing by platform

| Platform | Sentence length | Energy | Cut cadence |
|----------|-----------------|--------|-------------|
| TikTok | 5–10 words | Very fast | every 1–2s |
| YouTube Shorts | 8–12 words | Fast, punchy | every 2–3s |
| Instagram Reels | 10–15 words | Moderate | every 2–3s |

## Retention techniques (apply at least 2)

- **Open loops**: "I'll show you the fix in a second…"
- **Pattern breaks**: change angle, energy, or B-roll every 3–5s.
- **Direct address**: use "you" constantly.
- **Previews**: show the result before the process.
- **Pose questions** to keep watch-time up.

## How to use

Basic:
```
Write a 30s TikTok script about [topic] for [audience]. Tone: energetic. CTA: follow.
```
From a hook you already found:
```
Here's my hook: "[hook]". Build the full 45s Reels script + storyboard around it.
```
Adapt long → short:
```
Turn this 8-min YouTube script into a 60s Shorts version, keep the payoff.
```

## Output includes

- Complete script with timestamps
- Spoken VO lines + on-screen text overlays
- Shot-by-shot storyboard (visual / transition)
- Platform-specific pacing optimizations
- A CTA matched to the stated goal
- Estimated word count & duration check (≈150 wpm spoken; captions carry the rest)

## Tips for better scripts

1. Write for the ear — read it aloud.
2. Use contractions ("you'll", not "you will").
3. Short paragraphs — easy to read while filming.
4. Mark emphasis with **bold** / CAPS for stressed words.
5. Mark pauses with [pause] for dramatic beat.
6. Always pair every beat with a VISUAL — silent footage loses retention.
