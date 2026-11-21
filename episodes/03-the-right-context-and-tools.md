# Episode 3: The Right Context and Tools

**Status:** Workbook draft for recording. No video yet.

**Goal:** Give an AI the smallest set of current sources that can answer a defined job. When one important fact is missing, add one narrowly scoped, read-only way to get it.

**Audience:** Professionals and business owners who do not code.

Episode 2 set the job. This time the job stays the same. We change what the AI can see and show what that changes in the draft.

## The exercise: a workshop registration FAQ

Return to fictional Harbor Lane Consulting. Your task is to draft four answers for prospective attendees. Use three fresh chats with the same model, where practical, to reduce carryover. If your workspace can reuse chat history or saved memory, use temporary chats or turn off that carryover for the exercise if available. Use only the fictional material below; no real accounts or client data are needed.

Open [the demo kit](03-demo/README.md) for the exact copy/paste prompts, sources, run steps, and illustrative outputs.

| Run | Give it | Look for |
| --- | --- | --- |
| A: job only | The same job prompt, no sources | It marks missing facts or asks for a source instead of inventing policy. |
| B: current context | Same prompt plus the current rules and a labeled superseded copy | It uses the current rules over the old seat-hold and payment wording. Unanswered items stay visible. |
| C: one lookup | Same prompt and rules, plus permission to read one named operations file | It fills in the gaps from that file. Open the tool event yourself when available. If you supply the file text manually, say you did the lookup. |

## What to practice

- **Context** is the evidence you supply: the current policy, who wrote it, when it applies, and which older copy it replaces.
- **A tool** is how the AI can get evidence or act. A file reader may let it inspect one attachment; that does not mean it needs access to a shared drive or inbox.
- **A boundary** says what the assignment may do and where it stops. Prompt wording does not set real permissions. Check the tool's access through the workspace controls, and do not connect apps for this demo.
- **A check** is something you can verify: open the current rule and one overlooked detail, then compare both with the draft. A claimed source read is not proof that it happened.

## Take it to work

Pick a small draft-only task where an outdated document might change the answer. Name the current source, one missing fact, and the narrowest way to verify it. If a file read is unavailable or would grant too much access, have a person open the document and share only the relevant excerpt. No sending, publishing, or other external action is part of this exercise.

Continue to [Episode 4: Boundaries](04-boundaries.md) for the difference between an instruction, an actual permission, and a human approval point.
