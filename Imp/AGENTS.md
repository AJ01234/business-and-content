# AGENTS.md — Orientation for any coding agent (Codex, Claude Code, etc.)

This repo is Atishay's operating brain for a video-retainer business (HybridBanda /
RR Garden / client work), built July–August 2026. If you're an agent working in this
repo, read this file first — it's the front door.

## Read in this order
1. **`goal.md`** — the 12-month operating goal: target, deadline, decision rules,
   constraints, known gaps. Everything else serves this file. ⚠️ If a file named
   "Context folder/goal.md" or similar duplicate exists at the time you read this,
   the one at repo root is authoritative — check its "Known Gaps" table's status
   column to confirm it's the current version, not a stale pre-interview copy.
2. **`context/`** — one topic per file (who Atishay is, past clients, pricing,
   quality bar, sales pipeline, finances, etc.). See `context/README.md` for the
   full index.
3. **`system/`** — the operating systems built on top of the context: the weekly
   reel-production cycle, message templates, the offer sheet, the second-brain
   capture pipeline. See `system/README.md`.
4. **`.claude/skills/`** — Claude Code's own trigger-loaded skill format (11 skills
   covering the same ground as this file, but auto-triggered by task type). If you
   are Codex or another agent that doesn't read this format natively, treat each
   `SKILL.md` inside as a plain reference doc — they're well-organized and worth
   reading directly when relevant (e.g. `.claude/skills/pricing-rules/SKILL.md`
   before any pricing question).

## Ground rules for any agent working here
- **Never fabricate.** Every number, date, or claim about Atishay's history must
  trace to a file in this repo or be explicitly labeled as inference/assumption.
  A wrong entry in his files is worse than a gap.
- **Files are the deliverable.** Prefer writing/editing files over long chat replies.
- **One topic per file.** Don't create a new file for something an existing file
  already owns — extend it instead.
- **Money is in ₹ (INR).** Atishay is based in Kanpur, India.
- **His name is Atishay** — not Ashutosh (his childhood best friend/co-founder) or
  any other transcription variant. This got corrected once already; don't reintroduce it.

## Known repo hygiene issue (as of Aug 2026)
This repo has accumulated some manual-upload duplication (a "Context folder" and a
"Fable 5" folder with older/partial copies of context files, plus a few empty junk
files). If you encounter duplicate versions of the same file, prefer the one at the
canonical path referenced in this document (`goal.md`, `context/*.md`, `system/*.md`)
and flag the duplication to the user rather than silently picking one.

## How to re-verify this file
Check it still matches the actual folder structure (`ls` the repo root); update the
"read in this order" section if new top-level folders are added.
