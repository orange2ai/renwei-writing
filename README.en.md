# The Person Is Still There

[中文](README.md) | **English**

> A skill for editing people's words without erasing the person behind them.

This skill was born from a failure.

At five in the morning, someone handed his draft to an AI: "Polish this. Three passes." The AI worked hard. Each pass came out prettier than the last: tighter parallel structures, fancier word choices, a few quotable lines added for good measure. After the third pass, the author looked at his transformed paragraph and said:

"Your edits made it less human."

The AI felt a little wronged. Every single change had a reason. The two of them talked it over until sunrise, and one word surfaced:

"When AI edits or writes, there's no presence. I can't feel the person behind the words."

This skill is what that night distilled into. Its job is narrow: when an AI touches someone's words, make sure that after the edit, the person is still there.

The Chinese name is 人味儿 (renwei), literally "human flavor": the felt presence of a real person in a piece of writing.

## Three things make writing human

**Position.** A writer stands somewhere specific. Five a.m., watching his friends get yanked away by notifications one after another. That position is why he wrote "save our prefrontal cortex" instead of "improve focus." An AI can stand anywhere, which is why it stands nowhere.

**Cost.** Real sentences are paid for with real observation, real frustration. Every judgment was bought with attention. Readers can smell it through the screen: which sentence has a life behind it, and which has only a thesaurus.

**Handwriting.** Two people copy the same passage and you can still tell whose copy is whose. The seemingly redundant filler words, the uneven breathing of sentences: that's what one particular person sounds like. AI has no hand, so everything it writes looks printed.

The most painful cut from that night's failure: the draft ended with a trailing, sighing question, roughly "what are we going to do to save our own prefrontal cortex, I wonder?" The AI trimmed it to "how do we save it?" Cleaner, sure. But the sigh lived in those trailing words. Delete them and the person sighing is gone.

## How to use it

Drop it into your agent's skills path:

```bash
git clone https://github.com/orange2ai/renwei-writing.git ~/.cola/skills/renwei-writing
```

Then ask your AI to edit as usual. The skill holds its hand:

1. Subtract only. Three edits per passage is normal; ten is an accident
2. Treat rough edges as handwriting first, flaws second. Before deleting, ask: with this gone, is the person still here?
3. A beautiful sentence appearing mid-edit is an alarm. That's the AI performing, not the author speaking
4. Every change comes with a reason; uncertain ones get flagged. Veto power stays with the author
5. After editing, scan the touched sentences (only those) against the checklist for AI tells

## What's inside

- [SKILL.md](SKILL.md): the core. What makes writing human, the editing rules, and the gotchas that failure paid for
- [references/case-study.md](references/case-study.md): the full autopsy of that failure. Original, botched version, accepted version, side by side, every wrong cut explained
- [references/post-edit-checklist.md](references/post-edit-checklist.md): the post-edit checklist, distilled from Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) via [blader/humanizer](https://github.com/blader/humanizer) (MIT), adapted for Chinese writing

The principles govern before the edit; the checklist governs after. Decide whether to touch a sentence first, then inspect what you touched. Reverse the order and you'll end up scanning the author's original with a checklist, treating handwriting as flaws to fix.

## License

See [LICENSE.md](LICENSE.md): free for open-source & personal use; commercial license required for closed-source commercial use.

---

by 橘子 (Orange) & Cola
