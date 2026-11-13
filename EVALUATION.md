# Evaluation and review

This is a practical editorial checklist, not a validated scientific detector of AI text or a promise that a response is unrecognizable as AI-generated.

## Hard requirements

A draft fails review if it invents an unsupported claim or alters any material source fact, including a number, negation, condition, date, name, quotation, or degree of certainty. Fix these issues before assigning a style score.

The author's factual inputs and the target audience must be supplied or identified. Where information is missing, record what cannot be established.

## Human-review scorecard

Give each dimension 0, 1, or 2 points, for a maximum of 10:

| Dimension | 0 | 1 | 2 |
| --- | --- | --- | --- |
| Directness | Does not answer the task | Answer is buried | Leads with the answer or needed action |
| Clarity | Vague or awkward | Mostly clear | Idiomatic and immediately understandable |
| Audience fit | Wrong register | Mixed register | Fits actual reader/listener and medium |
| Structure | Mechanical or hard to scan | Some filler or repetition | Organization matches the subject |
| Editorial economy | Redundant or padded | Some unnecessary text | Each sentence has a clear purpose |

A high score does not establish factual correctness; that is a separate hard requirement.

## Test procedure

1. Save the original input and the constraints.
2. Apply one prompt without adding missing facts.
3. Compare source and output for names, numbers, conditions, scope, and uncertainty.
4. Read the output aloud. Check for awkward phrasing, repeated rhythms, contrived setups, and unnecessary recaps.
5. Have a human reader score the five dimensions. Record the reason for any low score.
6. Revise the prompt only where the evidence shows a recurring problem. Avoid tuning for one isolated sentence.

## Repeatable checks

The [editing exercises](examples/EDITING_EXERCISES.md) provide short examples with no real-person or commercial assertions. Preserve the given facts and ask whether the result is easier to use.

Keep a changelog of prompt revisions and their effect on real editing tasks. Do not publish private client text or personal data as test cases without permission and appropriate safeguards.
