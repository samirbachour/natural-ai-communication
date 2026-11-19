# Codex working model policy: natural-ai-communication

Effective 2026-11-18. Read README.md and the repository's existing architecture, safety, status and handoff documents before changing anything. These project rules do not supersede existing safeguards.

## Choose model and reasoning per task
- Small, well-scoped/reversible changes: GPT-6.2 Sol, low.
- Normal coding, tests, routine debugging: GPT-6.2 Sol, medium (default).
- Uncertain multi-file implementation: GPT-6.2 Sol, high.
- Complex architecture, security, migrations, concurrency and difficult debugging: GPT-6.2 Astra, high.
- Several interacting critical failures or extremely hard, high-risk design: GPT-6.2 Astra, extra high; max only if supported and necessary.

Project-specific escalation: Use Sol Medium for source-grounded editorial guideline updates; Astra High for design of rigorous evaluations and complex document-processing pipelines. Do not fabricate evaluation outcomes, sources or user facts, and preserve genuine stylistic differences.

## Model release updates and limits
When new Codex/Work models are announced, verify OpenAI's official availability, model IDs, reasoning support, plan/usage limits, coding reliability and task-specific benefit before changing these recommendations. Prefer a tested capable new model only when its actual fit improves. Never change a running model silently. Repository instructions inform recommendations but **cannot themselves switch the selected Codex model**; report the recommended model/effort if a selector change is needed. Preserve verified tests, local/Cloud access boundaries, protected operations and owner approvals.
