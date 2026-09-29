# Sell-Side Research Judgment — Codex Skill

[中文](README.md) | English

A reusable research-method skill for sell-side reports, macroeconomic themes, sector and company research, strategy outlooks, outlines and reviews.

**Test the logic, verify accessible evidence, then take a clear, defensible view.** The skill encourages professional judgment beyond description while distinguishing observed facts, mechanism inferences and forecasts. It requires weighing counterevidence, economic magnitude and offsets rather than forcing conviction.

## Installation

Clone or download this repository into your personal Codex skills directory so the entrypoint is:

```text
~/.codex/skills/sell-side-research-judgment/SKILL.md
```

Keep the supporting files and directories together. Start a new Codex conversation after installation. You can explicitly invoke `$sell-side-research-judgment` or allow automatic selection for relevant research work.

The default discovery entrypoint is `SKILL.md`, with a bilingual description. [SKILL.en.md](SKILL.en.md) contains the full English instructions and links to English examples. One installation serves both languages; the requested output language controls the response language. Do not install a second copy or rename the English file over the entrypoint.

Example request:

> Use $sell-side-research-judgment to review this outline. First assess the logic, then whether accessible evidence supports it, and finally give a clear baseline judgment and usable revisions. Respond in English.

## Contents

- [SKILL.md](SKILL.md): Chinese entrypoint and core rules.
- [SKILL.en.md](SKILL.en.md): complete English counterpart.
- [Chinese examples](references/judgment-examples.md) / [English examples](references/judgment-examples.en.md): eight methodological cases covering causality, extrapolation, portfolio behavior, forecasts, price drivers, technical errors, upgrades and net effects.
- `agents/openai.yaml`: display metadata and invocation policy.

The skill provides a method, not ready-to-cite data or a predetermined investment view. Verify project-specific facts, sources, definitions and conclusions. Keep both language versions aligned when changing the rules.
