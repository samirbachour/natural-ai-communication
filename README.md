# Natural AI Communication

An open-source guide to more natural, accurate AI-generated writing and spoken responses.

The project contains **original editorial guidelines, reusable prompts, fact-preserving editing exercises, and a review rubric**. Its goal is to reduce formulaic language while preserving the writer's purpose, audience, and factual details.

It is **not** a merged fork of other repositories, an AI-detector evasion tool, a voice-synthesis engine, or a replacement for an AI model. No model, account setting, or voice system changes simply because you use this repository.

## Get started

| What you want | Start here |
| --- | --- |
| Make everyday ChatGPT writing clearer and more natural | [Custom Instructions prompt](prompts/CHATGPT_CUSTOM_INSTRUCTIONS.md) |
| Revise an existing draft without adding facts | [Fact-preserving rewrite prompt](prompts/REWRITE_WITHOUT_INVENTING.md) |
| Make conversational replies less scripted and easier to hear | [Spoken-response prompt](prompts/CONVERSATIONAL_VOICE.md) |
| Understand the editorial method | [Writing and conversation guide](GUIDE.md) |
| Review results systematically | [Evaluation checklist](EVALUATION.md) |
| See neutral before-and-after exercises | [Editing exercises](examples/EDITING_EXERCISES.md) |

There is nothing to install. Open the relevant file, copy the prompt, and adapt the marked fields to your audience and purpose. For account-wide use, review and save your chosen instructions in your ChatGPT personalization settings.

## Editorial priorities

- **Facts first.** Keep names, numbers, dates, units, conditions, citations, uncertainty, and limitations accurate.
- **Write for the audience.** A spoken answer, a technical report, and an advertisement should not share one rigid template.
- **Lead with the point.** Avoid rehearsed introductions and summaries that simply repeat the answer.
- **Use ordinary professional English.** Replace awkward phrasing and vague claims with specific, supported language.
- **Edit the structure.** Repair repetitive pacing, formulaic hooks, forced contrasts, and contrived three-part phrases when they weaken the piece.
- **Retain nuance and personality.** Humor, rhetorical devices, long explanations, and lists remain useful when the task calls for them.

These are editorial choices, not absolute bans on particular words. The user or author retains control over the intended style.

## How to evaluate a change

1. Keep a copy of the original source.
2. Apply the prompt to text you are authorized to use.
3. Compare the result with every material fact, condition, and qualification in the original.
4. Review the revised text aloud and score clarity, directness, audience fit, structure, and economy.
5. Refine the instructions when a repeatable issue appears.

The provided exercises are **constructed editing examples**, not a scientific benchmark or evidence that prompts will consistently pass AI-writing detectors.

## Spoken conversation versus text

The spoken-response prompt can help an assistant deliver shorter, clearer verbal answers. It **does not change the underlying speech model**, audio quality, speed, or turn-taking mechanism. Those depend on the application and its available settings.

## Sources and independent authorship

The editorial approach was informed by the publicly available [Humanizer](https://github.com/blader/humanizer) and [Anti-Slop Writing Guide](https://github.com/louisfb01/ai-engineering-cheatsheets/blob/main/Anti_Slop_AI_Writing_Guide.md). This repository is independently written; it does not redistribute their source files or evaluation datasets. See [Credits and attribution](CREDITS.md) for the licensing distinction.

## License and contributions

Original materials in this repository are licensed under [MIT](LICENSE). Suggestions and corrections are welcome under the [contribution guidelines](CONTRIBUTING.md). Do not submit confidential conversations, identifiable customer text, or proprietary examples without permission.
