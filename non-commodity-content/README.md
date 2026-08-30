# Non-Commodity Content

A skill for Claude that interviews you for real evidence, examples, and point of view **before** it drafts a blog post, pillar page, or landing page.

## The problem it solves

Ask an AI for a landing page and you get a competent page that any competitor in your category could have published. That's commodity content, and it's the thing Google's quality systems are built to filter out.

Google doesn't care whether a human or an AI wrote the page. It cares about the purpose and value of the finished result. AI Overviews and AI Mode run on the same index and ranking systems as regular Search, so there's no separate trick that makes content perform there — it's the same bar it has always been: original thinking, first-hand experience, specific examples, clear authorship, trustworthy sources.

The catch is that AI can't supply any of that. It has to come from you.

## What the skill does

1. **Interviews you first.** It won't draft on the first turn. It asks who the page is for, what you know that others don't, what specific numbers and client situations you can cite, and where you actually disagree with the consensus. Questions branch by page type — pillar pages get scope and internal-linking questions, landing pages get offer, objection, and proof questions.
2. **Pushes back on vague answers.** "We help clients scale" gets a follow-up until it becomes a number or a real situation.
3. **Leaves gaps visible.** Anything you don't answer becomes a `[NEEDS INPUT: ...]` placeholder in the draft. It won't invent a statistic, customer quote, or case study to fill the hole — an invented specific reads as authoritative and survives editing, which makes it worse than a blank.
4. **Flags what's still generic.** Every draft ends with a list of placeholders plus any section that would fail the "could a competitor have written this?" test.

## Scope

This skill handles the **first stage** of content creation: substance. It deliberately doesn't cover word count, formatting, heading structure, or page templates — those belong in separate skills so this one stays focused on getting real material out of your head.

## Installation

See the [root README](../README.md) for install instructions. In short:

```bash
git clone https://github.com/daveferrick/claude-skills.git
cp -r claude-skills/non-commodity-content ~/.claude/skills/
```

## Usage

Just ask for the page. The skill triggers on requests for blog posts, pillar pages, landing pages, service pages, and articles — you don't need to mention SEO or invoke it by name.

> "I need a pillar page on HubSpot pipeline management."

Expect questions before you get a draft. That's the point.

## Credit

Built from a [LinkedIn post](https://www.linkedin.com/feed/update/urn:li:activity:7499753057694425088) by [Thorstein Nordby](https://www.linkedin.com/in/thorsteinnordby) summarizing Google's guide *Optimizing your website for generative AI features on Google Search*.

The post prompted this skill; the author hasn't reviewed or endorsed it.

## License

MIT
