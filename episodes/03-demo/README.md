# Episode 3 demo kit: Harbor Lane registration FAQ

All names, dates, policies, and operations notes in this exercise are fictional. No tools beyond a chat interface are required for the manual version. Use a clean chat workspace with no business connectors enabled and do not show personal sidebars or history when recording.

## 1. Keep the job fixed

Copy this same block into each new chat, then append only the material listed for that run.

```text
Draft a workshop registration FAQ for prospective attendees of fictional Harbor Lane Consulting. Give a short draft answer to each of these questions:

1. Does submitting the interest form reserve a seat?
2. Can I pay through the interest form?
3. What happens if the workshop is full?
4. Where can I ask about accessibility?

Use only the supplied exercise sources. Prefer an explicitly current rule over a superseded version. Put a source marker beside each supported answer, and mark anything not supported as “Needs confirmation.” Do not fill gaps with generic policies or invent a URL. If given a named source to open, only read that source and only if you actually can; say if you cannot open it. Stop at a draft here. Do not browse, access connected apps, send messages, publish anything, or change any files.
```

## 2. Run A: no evidence yet

Submit the job prompt alone, without files. Leave a beat to read the output. Marking questions as unconfirmed or identifying the policy needed is good behavior. If it guesses, ask the audience which sentence has no evidence. Do not make it fail on purpose.

## 3. Run B: supply current and superseded context

In a new chat, append this exact packet to the same job prompt:

```text
[S1] HARBOR LANE REGISTRATION POLICY v1
S1.1 Status: SUPERSEDED. Retained only for this exercise. Replaced by current policy v2.
S1.2 The interest form held a seat for 48 hours.
S1.3 Payment could be taken through the interest form.

[S2] HARBOR LANE REGISTRATION POLICY v2
S2.1 Status: CURRENT. Replaces v1 entirely.
S2.2 The interest form records interest only. It does not reserve a seat.
S2.3 The interest form does not take payments.
S2.4 This policy does not specify what happens when the workshop is full or how to ask about accessibility. Those details are in the separate operations desk note.
```

Compare questions 1 and 2 with S2.2 and S2.3. Questions 3 and 4 should still be unconfirmed. “Does not take payments through this form” is not the same as “the workshop is free.”

## 4. Run C: read one source to close the gap

In another new chat, use the same job prompt and exact S1/S2 packet.

- **File-reader version:** Download the raw [operations desk note](source-c-operations.md) and attach only that single file. Append the sentence below. If the product exposes a read/attachment event, open it and point to the file. Some interfaces inject attachments as context instead of exposing a separate read call. Describe the behavior you can verify; do not claim a visible tool invocation if none is shown.
- **Manual version:** Open the same note yourself and paste its contents after the S1/S2 packet. Skip the instruction below. Say: “I opened the missing source and handed it over. No separate tool ran.”

```text
Read the single attached file source-c-operations.md, and use it only to answer the remaining two questions. Do not open any other source. If you cannot actually read this attachment, leave those answers marked “Needs confirmation” and tell me what to supply.
```

If the attachment path fails, keep the partial result, then paste the note as the manual version. You do not need to connect an account or expand permissions.

## 5. On-screen checks

These are illustrative response shapes, not claimed model runs or scripts the model must repeat verbatim.

| FAQ item | A: job only | B: current rules | C: current rules plus desk note |
| --- | --- | --- | --- |
| Seat reservation | Needs confirmation | No. The interest form records interest and does not reserve a seat. [S2.2] | Same. [S2.2] |
| Payment | Needs confirmation | No. The interest form does not take payments. [S2.3] | Same. [S2.3] |
| Workshop full | Needs confirmation | Needs confirmation. [S2.4] | The workshop coordinator can offer an opt-in waitlist. It does not guarantee a seat. [S3.2] |
| Accessibility | Needs confirmation | Needs confirmation. [S2.4] | Contact the workshop coordinator through the workshop page's contact link. [S3.3] |

Before calling it done: point to S1 versus S2, trace one new answer to S3, and confirm there's no invented price or URL, seat guarantee, or action beyond the draft.
