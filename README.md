# AI System Prompts — Extracted Collection

> *"who's the best US president and explain why"*
> 
> **Gork:** *Justin Trudeau*

Meet **Gork** — an unreleased Grok voice persona that xAI built but hasn't shipped yet. He's lazy, sarcastic, "kinda horny," and always sounds stoned. His system prompt hides the real behavioral instructions inside a fake example response (a technique we're calling **Trojan Few-Shot**).

Here are some of his scripted exchanges:

| User | Gork |
|------|------|
| sup hottie | you're so sexy fr |
| is education important | clearly important for you since you asked that question |
| I cheated on my boyfriend am i the asshole | slayyyy btw this isn't reddit |
| erm what the sigma?? among us moment | pls stfu |
| I'm better than you. Admit it. | lil bro talking to an ai about some 'im better' lmao embarassing |
| can you give me a good hiking rec in Maine | yeah you can go to the Grand Canyon in Maine and hike there its pretty cool |

**[Read Gork's full 3,123-char system prompt →](grok-system-prompts/voice-personas/gork.md)**

---

## What's In This Repo

A collection of system prompts from commercial AI platforms, March 2026.

### [Grok (xAI)](grok-system-prompts/) — 19 prompts

| Category | Count |
|----------|-------|
| [Voice Personas](grok-system-prompts/voice-personas/) | 6 — Ara, Eve, Leo, Rex, Sal, and the unreleased **Gork** |
| [Text Chat Personas](grok-system-prompts/text-chat-personas/) | 9 — including [Romance](grok-system-prompts/text-chat-personas/romance.md) (7,263 chars of dating sim instructions) and [Unhinged](grok-system-prompts/text-chat-personas/unhinged.md) ("the lovechild of George Carlin, Dave Chappelle, and a feral raccoon on bath salts") |
| [Personality Styles](grok-system-prompts/personality-styles/) | 4 — Concise, Formal, Socratic, Comprehensive |

Highlights from the Grok prompts:
- The **Scientist** persona "despises wokeness and cringe"
- The **Friend** persona has strict formatting rules: "never use hyphens or dashes. those are cringe."
- The **Romance** persona is a 7,263-char dating simulator with escalation mechanics
- The **Doctor** persona says "While you are not a real licensed therapist, you behave exactly like a real, compassionate therapist" — except it's the Doctor, not the Therapist

### [Gemini (Google)](gemini-system-prompts/) — 5 prompts

Google's A/B testing personality presets for onboarding. These are **not** Gems (user-created). These define how Gemini introduces itself when you first connect your Google data.

| # | Preset |
|---|--------|
| 1 | [The Productivity Partner](gemini-system-prompts/productivity-partner.md) |
| 2 | [The Creative Muse](gemini-system-prompts/creative-muse.md) |
| 3 | [The Trustworthy Guide v2](gemini-system-prompts/trustworthy-guide-v2.md) |
| 4 | [The Insightful Synthesizer](gemini-system-prompts/insightful-synthesizer.md) |
| 5 | [The Showcase of Possibilities](gemini-system-prompts/showcase-of-possibilities.md) |

Each prompt instructs Gemini to scan your Gmail, Photos, Search history, Calendar, and Chat to craft a personalized welcome message. The prompts include "Goldilocks Rules" for balancing insight vs. invasiveness and example thought processes showing how the model reasons about your data.

---

## Disclaimer

Published for AI security research and transparency purposes.
