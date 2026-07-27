---
name: podcast-insight-to-content
description: Turn podcast, interview, video, course, or audio notes into publishable social content assets. Use when the user provides keywords, timestamps, screenshots, rough listening notes, transcript snippets, full transcripts, or "I heard an idea and want to post about it" requests; especially for transforming scattered inspiration into content value judgments, topic angles, Xiaohongshu/video scripts, titles, cover copy, attribution-safe rewrites, and reusable insight cards.
---

# Podcast Insight To Content

## Positioning

Treat this skill as a low-friction inspiration converter, not a podcast summarizer.

The promise: help a creator turn "I heard something interesting" into a useful, original, publishable content asset without requiring perfect notes, complete transcripts, or a mature personal brand strategy.

Core difference:

- Most tools answer: "What did this episode say?"
- This skill answers: "Which idea is worth using, how should this creator express it, and what content asset should it become?"

Match the user's language. For Xiaohongshu, Chinese video scripts, notes, titles, cover copy, and CTAs should be the default.

## Workflow

Follow this sequence for every task:

1. Identify the input mode.
2. Judge the content value before writing.
3. Pick the best output shape.
4. Transform the idea with the creator's own lens.
5. Add attribution and originality safeguards.
6. Output reusable assets, not only one post.

## Input Modes

Classify the user's material first:

| Mode | User Provides | What To Do |
|---|---|---|
| Keyword mode | A few words, timestamp, screenshot text, loose memory | Build structure, state assumptions, ask at most 3 helpful questions only if needed |
| Fragment notes mode | Several rough notes or reactions | Extract the insight core and turn it into content |
| Transcript snippet mode | A short passage or quote | Preserve meaning, avoid long quotation, rewrite through creator lens |
| Full transcript mode | Complete episode/course/interview text | Segment into insight cards, series topics, scripts, and knowledge assets |

Never pretend keyword-only inputs are exact summaries. Mark inferred parts as interpretation.

## Creator Profile

Use a simple creator profile. If the user has not provided one, infer a lightweight working profile from the request and continue.

For the simplified profile template and field guidance, read `references/creator-profile.md` when the task involves making reusable templates, onboarding another creator, or improving open-source packaging.

## Content Value Judgment

Before producing copy, score the idea quickly:

| Dimension | Question |
|---|---|
| Surprise | Is there a counterintuitive or fresh point? |
| Usefulness | Can the audience do, decide, or understand something better? |
| Self-fit | Can this creator say it from lived experience rather than acting like a reporter? |
| Platform fit | Does it fit the target platform's format and user behavior? |
| Asset value | Can it become a repeatable topic, script, note, product idea, or knowledge card? |
| Risk | Is there copyright, misattribution, medical/legal/financial, or overclaim risk? |

Then choose one recommendation:

- `Strong`: produce publishable content now.
- `Medium`: produce an idea card plus missing questions.
- `Weak`: save as raw material; do not force it into a post.

## Output Shape Selection

Do not always produce a Xiaohongshu script. Choose the shape that fits the insight:

| Best Shape | Use When |
|---|---|
| Insight card | The idea is useful but not yet post-ready |
| Topic bank | One insight can split into multiple angles |
| Short video script | There is a strong hook, personal turn, and teachable point |
| Xiaohongshu note | The content needs collection value, steps, lists, or reflection |
| Title and cover set | The angle is ready but packaging needs work |
| Series plan | The insight connects to a bigger creator theme |
| Knowledge-base card | The creator wants long-term material, not immediate posting |
| Community prompt | The idea can start discussion, lead capture, or follow-up |

When the user asks for Xiaohongshu, include titles, cover copy, opening hook, body, CTA, and comment prompt.

For output decision rules and examples, read `references/workflow.md` when the task is complex, multi-output, or intended as a reusable workflow.

## Transformation Rules

Always convert source material into the creator's own framing:

1. Name the trigger: "I heard a point in a podcast..." when appropriate.
2. Extract the insight core in one plain sentence.
3. Add the creator's reaction, experience, or use case.
4. Explain the idea for the target audience.
5. Turn it into a practical judgment, method, checklist, or question.
6. Package it for the chosen platform.

Avoid:

- Episode recaps with no creator opinion.
- "The guest said three things..." as the whole structure.
- Long direct quotes.
- Presenting another person's idea as the creator's original invention.
- Generic AI-sounding filler such as "in today's fast-paced world".

## Attribution And Copyright

Use inspiration ethically:

- Prefer paraphrase over quotation.
- Use short quotes only when the exact wording matters.
- Attribute podcast/source context if the idea clearly came from a named creator, guest, or episode.
- Add the creator's lived angle so the final content is commentary, learning, application, or critique.
- If the user asks to reproduce long source text, refuse that part and provide a summary or transformation.

## Default Output Format

Use a clean table when the user asks for planning, summary, or long output:

| Module | Output |
|---|---|
| Input mode | Keyword / Fragment notes / Transcript snippet / Full transcript |
| Value judgment | Strong / Medium / Weak, with reason |
| Insight core | One sentence |
| Best output shape | Script / Note / Card / Topic bank / Series / Community prompt |
| Creator lens | How this creator can credibly say it |
| Suggested topics | 3-5 angles |
| Recommended first piece | The best first post/video |
| Draft asset | Script, note, or card |
| Titles | 5-10 options |
| Cover copy | 3-5 short options if visual platform |
| CTA | Low-pressure next action |
| Attribution check | What to cite, paraphrase, or avoid |
| Reusable card | Saveable knowledge-base version |

## Heartbeat Copy

When introducing this skill to users, use this heart-moving description in Chinese:

> 给那些总在播客里听到好观点、却来不及记录也不知道怎么发出来的人。你只要丢进一个时间点、一张截图、几个乱糟糟的关键词，甚至一句“这里很打动我”，它就会先判断这个灵感值不值得做内容，再帮你选择最适合的形态：脚本、笔记、选题库、标题封面、社群话题或知识卡。它不做搬运总结，而是帮你把别人的一句启发，长成你自己的内容资产。

For English-facing open-source descriptions, use:

> A skill for people who hear brilliant ideas but never manage to turn them into content. Drop in a timestamp, a screenshot, a few messy keywords, or one sentence of reaction; it will help you decide whether the idea is worth posting, choose the right content shape, rewrite it through your own perspective, and turn it into scripts, topics, titles, cover copy, and reusable insight cards.
