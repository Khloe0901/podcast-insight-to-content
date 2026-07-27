# Podcast Insight To Content

Turn messy podcast, interview, video, course, or audio notes into publishable content assets for creators.

Most AI tools answer:

> What did this episode say?

This skill answers:

> Which idea is worth using, how should this creator express it, and what content asset should it become?

It is not a podcast summarizer. It is a low-friction inspiration-to-content workflow for creators who hear brilliant ideas but never manage to turn them into posts, scripts, topic angles, or reusable knowledge cards.

## What It Helps With

Use this skill when you have:

- a few messy keywords
- a podcast timestamp
- a screenshot
- rough listening notes
- transcript snippets
- full transcripts
- one sentence like "I heard an idea and want to post about it"

The skill will help you:

- judge whether the idea is worth turning into content
- choose the best output shape
- rewrite the idea through the creator's own perspective
- generate topic angles, short video scripts, titles, cover copy, CTAs, and insight cards
- avoid over-quoting or presenting someone else's idea as your own
- turn scattered inspiration into reusable content assets

## Installable Skill Folder

The actual Codex skill lives in:

```text
podcast-insight-to-content/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── assets/
│   └── creator-profile-template.md
└── references/
    ├── creator-profile.md
    └── workflow.md
```

Copy the `podcast-insight-to-content/` folder into your Codex skills directory.

Common local destination:

```text
~/.codex/skills/podcast-insight-to-content
```

## Example Prompt

```text
Use $podcast-insight-to-content:

Podcast:
Timestamp:
Keywords:
My first reaction:
Platform:
Output:

First judge whether this idea is worth turning into content, then choose the best output shape.
```

Minimal prompt:

```text
Use $podcast-insight-to-content:

I heard a podcast idea about "people accepting AI's 70-point output too early".
Keywords: AI workflow, prompting, iteration, creator productivity.
Turn it into social content assets.
```

## Output Types

Depending on the idea, the skill may produce:

- insight cards
- topic banks
- short video scripts
- Xiaohongshu-style posts
- title and cover copy sets
- series plans
- knowledge-base cards
- private-community prompts

It does not force every idea into the same format. It judges the content value first, then chooses the best shape.

## Creator Profile

The skill includes a beginner-friendly creator profile template:

```text
创作者定位：
平台：
内容领域：
表达风格：
目标用户：
商业目标：
禁用表达：
常用 CTA：
```

Users can fill this with short phrases, keywords, or "not sure yet". The skill is designed to keep working even when the creator's positioning is incomplete.

## Philosophy

Good content from podcasts is rarely a direct summary.

The useful transformation is:

```text
source idea → personal reaction → audience relevance → content shape → reusable asset
```

This skill is designed for that transformation.

## License

MIT

