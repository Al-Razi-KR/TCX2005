# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a personal course materials repository for **TCX2005: Information Systems, Management and Organisations** at NUS. It stores lecture notes, announcements, assignments, quizzes, and project materials — not a software project.

## Structure Convention

- `announcements/` — Instructor announcements, named by date and topic
- `calendar.md` — Master calendar of all deadlines, lessons, and tasks
- `assignments/` — Assignment screenshots and written responses
- `book/` — Textbook PDF (Laudon & Laudon) and chapter summaries
- `lessons/` — Lecture slides, notes, and pre-recorded lecture summaries
- `project/` — Group project materials and deliverables
- `quizzes/` — Weekly short quiz materials and answers
- `resources/` — Course rules, assessments, and helpful links

## Custom Skills

### `transcript` skill
Defined in `.claude/skills/transcript/SKILL.md`. Invoke with `/transcript` or paste a transcript and Claude will trigger it automatically.

It will:
1. Create a structured notes file in `lessons/` with a `_notes.md` suffix
2. Create a corrected raw transcript in `transcripts/`
3. Output a table of all detected inaccuracies with confidence levels and timestamps

Only high-confidence corrections are auto-applied. Medium and low confidence issues are reported in the table for user confirmation.

**File naming:** `L{N}_Part-{X}_{Description}` — e.g. `L1_Part-2_Information-Systems-Basics`

---

## Key Course Details

- **Instructor:** Dr. Prakash Sukhwal (pcsdisa@nus.edu.sg)
- **Textbook:** *Management Information Systems: Managing the Digital Firm*, 17th Ed. — Laudon & Laudon
- **Semester Dates:** May 14, 2026 (L1) → July 11, 2026 (Final Exam)
- **Venue:** LT15
- **Project Theme:** Digital Transformation (groups of 5–6, register on Canvas under People > Project Groups)
- **Assessments:** Weekly short quizzes + Final exam (no assignments, no mid-term)
