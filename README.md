# claude-skills
Skills I use with Claude, mostly for content and SEO work.

A skill is a folder with a `SKILL.md` inside it. Claude reads the description, decides when it's relevant, and follows the instructions. Each skill in this repo has its own README with details.

## Skills

| Skill | What it does |
|---|---|
| [non-commodity-content](non-commodity-content/) | Interviews you for real evidence and point of view before drafting a blog post, pillar page, or landing page. |

## Installation

**Claude.ai / Claude apps:** download the `.skill` file for the skill you want from [Releases](https://github.com/daveferrick/claude-skills/releases), then upload it in Settings → Capabilities → Skills.

**Claude Code:** clone the repo and copy the folders you want into your skills directory.

```bash
git clone https://github.com/daveferrick/claude-skills.git
cp -r claude-skills/non-commodity-content ~/.claude/skills/
```

To build a `.skill` file yourself, zip the skill's folder and rename the extension to `.skill`. The folder name must match the `name` field in its `SKILL.md`.

## Design notes

These are built to be narrow and composable rather than one large do-everything skill. `non-commodity-content` handles substance and deliberately ignores word count and formatting, so those can live in their own skills and be swapped or skipped without touching the interview logic.

## License

MIT
