# case-study-interview

A Claude skill that interviews you about a past project, one topic per chat, and turns the conversation into material for a marketing case study. It was built for a fractional marketing / fractional CMO practice and is designed for voice dictation.

## What it does

Claude acts as an interviewer first and a writer second. It moves through four phases:

1. **Open the topic.** Claude confirms which project or offering the chat covers and what problem the client or company faced.
2. **Brain dump.** On request, Claude stays in listen mode and gives only short acknowledgements until you say you're done.
3. **Interview.** Claude asks one question at a time across seven threads:
   - the numbers
   - the mechanics
   - likely reader objections
   - decision rules
   - effort and cost
   - downstream team impact
   - proof
4. **Wrap-up.** Claude says when it has enough and asks what you want next.

## Deliverables

- **Rough outline (in chat).** Section-by-section flow, no refined copy, led by a four-beat TL;DR: problem, insight, move, payoff. Length follows the content.
- **Interview summary doc (on request only).** A faithful record of the interview for reference in other projects. Uncertain figures are marked as approximate.

## Ground rules built in

- One question per turn
- No invented numbers, names or baselines
- In-house work framed honestly as work you led
- No artifacts or docs without asking first
- Each case study's length sets no precedent for the next

## Installation

Copy the `case-study-interview` folder into your Claude skills directory, or upload `SKILL.md` through Claude's skill settings.

## Usage

Start a new chat for each topic and say something like:

> Interview me about the webinar program I ran for a case study.

## Files

- `SKILL.md`: the skill instructions Claude follows
- `README.md`: this file
