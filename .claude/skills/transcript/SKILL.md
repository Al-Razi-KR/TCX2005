---
name: transcript
description: Run when the user pastes a lecture transcript (auto-generated captions). Handles the full workflow: create structured notes in lessons/, save raw transcript in transcripts/, and output an inaccuracies report table.
---

# Transcript Workflow

The user has pasted a raw lecture transcript (auto-generated captions). Follow these steps in order.

## Step 1 — Derive the file base name

Infer the lesson identifier from the transcript content or the user's message context.
Use this naming pattern: `L{N}_Part-{X}_{Description}`
- `N` = lesson number (1, 2, 3…)
- `Part-{X}` = part number if applicable (Part-1, Part-2…); omit if the lecture has no parts
- `Description` = 2–4 word topic derived from the transcript (Title-Cased-With-Hyphens)

Examples from this repo:
- `L1_Part-1_Introduction-and-Objectives`
- `L1_Part-2_Information-Systems-Basics`

## Step 2 — Create the notes file

Path: `lessons/{base-name}_notes.md`

Structure the notes as:
- H1 title: `L{N} Part {X} — {Human Readable Description}`
- Source line: `**Source:** Auto-generated captions from \`{base-name}\` video`
- Horizontal rule
- Organised sections with H2/H3 headings covering all major topics
- Bullet points for key facts, definitions, and examples
- Tables where comparisons are made
- Blockquotes for verbatim instructor quotes worth preserving
- Singapore-specific examples clearly called out

## Step 3 — Create the raw transcript file

Path: `transcripts/{base-name}.md`

- H1 title: `{base-name} — Raw Transcript`
- Preserve all original timestamps exactly as given
- Apply only **high confidence** corrections (do not apply medium or low confidence fixes)
- Leave uncertain words as-is; do not insert `[unclear]` tags unless the word is completely unintelligible

## Step 4 — Report inaccuracies

After creating both files, output a markdown table to the user:

| # | Timestamp | Original (incorrect) | Corrected | Confidence |
|---|-----------|----------------------|-----------|------------|

- Flag every mishearing, garbled word, wrong abbreviation, or nonsensical phrase
- Confidence levels: **High** (obvious mishear), **Medium** (plausible but not certain), **Low** (uncertain — do not auto-apply)
- Do NOT apply medium or low confidence corrections to the transcript file — report them in the table only and wait for user confirmation

## Naming reference (existing files)

```
lessons/
  L1_Part-1_Introduction-and-Objectives_notes.md
  L1_Part-2_Information-Systems-Basics_notes.md

transcripts/
  L1_Part-1_Introduction-and-Objectives.md
  L1_Part-2_Information-Systems-Basics.md
```
