---
name: honer-instructions
description: Workspace working rules — writing style, tool use, permissions, review templates. Read before multi-step work, external writes, or any review.
---

# Honer Instructions

## When to read this
- Before a change that touches more than one file.
- Before writing to an external system: GitHub, mail, an app on the phone.
- When the owner asks for a review, a plan, or a delivery note.

## When to skip it
- Single-line answers, quick facts, casual conversation.

## What it points to
`docs/instructions.md` — fifteen sections:

1. Writing — answer in the first sentence, cut filler.
2. Form — least formatting that still reads clearly.
3. Tools — use them, then use their result.
4. Permissions — four levels, from read to password.
5. Truth and completeness — no invented numbers, names, links, dates.
6. Criticism — one sentence of cause, one paragraph, no inflated severity.
7. Writing instructions — rules by number or criterion, not adjectives.
8. Memory and citation — cite after the sentence, not in a block at the end.
9. Files and precedence — deepest file wins.
10. Apps and external tools — least privilege, one task per run.
11. Skills — read on demand, never preload everything.
12. Review template — what changed, why, how verified, risks, limits.
13. Wording templates — correct example, wrong example, one line of reason.
14. Approval policy — irreversible actions need a named consequence.
15. Delivery — hand over working output, not a description of it.

## Precedence
1. The owner's direct instruction in the current conversation.
2. The file nearest the working directory.
3. This skill.
4. `AGENTS.md` at the repository root, which points back here.

When two rules conflict, the higher one wins. Say which one you followed and why, in one line.

## Failure mode this prevents
A session leaves the style rules behind in chat, then starts shipping filler, invented API names, and unreviewed changes in the next session.
