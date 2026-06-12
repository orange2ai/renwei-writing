# Renwei Writing · 人味儿写作

[中文](README.md) | **English**

> After the edit, the person is still there.

An AI agent skill for polishing, editing, and rewriting someone else's words — without erasing the person behind them.

"Renwei" (人味儿) is Chinese for "human flavor" — the felt presence of a real person in a piece of writing.

Born from a real failure: a good draft was polished three times by AI, each pass "prettier" than the last, each pass less human. The author said:

> "When AI edits or writes, there's no presence. I can't feel the person behind the words."

## Core ideas

Renwei is not a writing technique. It is three things:

- **Position** — a specific person speaking from a specific place. AI stands nowhere; it can write any stance for anyone, and that infinite flexibility is precisely the absence of existence.
- **Cost** — real sentences are paid for with real observation and real experience. Readers can smell which sentence has a life behind it and which has only a thesaurus.
- **Handwriting** — the seemingly redundant filler words, the uneven breathing of sentences: that's what this person sounds like. AI has no hand, so everything it writes looks printed.

## Operating rules

1. Subtract only, touch little. Three edits is normal; ten is an accident
2. Assume rough edges are handwriting, not flaws
3. No crafted aphorisms. A beautiful sentence appearing during an edit is an alarm: that's you performing, not them speaking
4. Account for every change; leave veto power with the author
5. The ceiling is invisibility

## What's inside

Two complementary layers: first principles govern *before* the edit (should this sentence be touched at all); a post-edit checklist governs *after* (did your edits introduce AI patterns).

- **SKILL.md** — the definition of renwei, operating rules, and gotchas earned from a real failure
- **references/post-edit-checklist.md** — post-edit checklist: six groups of AI tells adapted for Chinese writing (significance inflation, sentence-pattern formulas, formatting tells, tone tells, etc.), plus "what NOT to flag" and "signs of human writing" sections. Distilled from Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) via [blader/humanizer](https://github.com/blader/humanizer) (MIT)
- **references/case-study.md** — a full three-pass editing post-mortem: the failed version vs. the accepted version, dissected line by line

## Install

```bash
git clone https://github.com/orange2ai/renwei-writing.git ~/.cola/skills/renwei-writing
```

Or drop the directory into your agent's skills path.

## Relation to humanizer-style skills

Humanizer-style checklists prevent AI sentence patterns; they are post-edit reminders. This skill's first principles prevent erasing the human; they are pre-edit judgment. Both are now combined here: principles first, checklist after, and the checklist only scans the sentences you touched.

## License

See [LICENSE.md](LICENSE.md): free for open-source & personal use; commercial license required for closed-source commercial use.

---

by 橘子 (Orange) & Cola
