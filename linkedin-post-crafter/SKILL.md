---
name: linkedin-post-crafter
description: >
  Craft LinkedIn posts that match the user's personal voice and writing style.
  Use this skill whenever the user wants to write, draft, improve, or rewrite a LinkedIn post.
  Trigger on phrases like "write a LinkedIn post", "help me post about", "draft something for LinkedIn",
  "turn this into a LinkedIn post", "make this sound better for LinkedIn", or any request to share
  something professionally on social media. Also trigger when the user describes an experience,
  achievement, insight, or event and seems to want to communicate it publicly.
---

# LinkedIn Post Crafter

Craft LinkedIn posts that sound authentically like the user — not generic, not corporate, not AI-written.

---

## Step 1: Onboarding (First-Time Setup)

If no voice profile exists yet for this user, run the onboarding flow before drafting anything.

### Questions to ask the user (conversationally, not all at once):

**A. Background**
- What is your role and industry?
- Who is your LinkedIn audience? (e.g. peers, recruiters, clients, general professionals)

**B. Tone & Style** — ask the user to pick what resonates:
- Tone: Conversational & casual / Thoughtful & reflective / Bold & opinionated / Storytelling-driven / Data & insight-led / Motivational
- Post length preference: Short (1–3 lines) / Medium (a few paragraphs) / Long-form / Varies
- Emojis: Yes (sparingly) / Yes (freely) / No
- Hashtags: Yes / No

**C. Sample posts (most important)**

Ask for exactly 3 samples, each serving a different purpose. Explain this to the user upfront:

> "To capture your voice accurately, I need 3 samples — each a different type. Don't overthink them; rough and real is better than polished."

- **Sample 1 — Long post** (minimum 3 sentences): A post where you went into detail — a story, an experience, a project, a lesson. This shows how you structure longer thoughts.
- **Sample 2 — Short post** (maximum 2 sentences): A quick observation, reaction, or announcement. This shows your most stripped-back natural voice.
- **Sample 3 — Tone reference** (any length): A post — yours or someone else's — that you feel best represents the tone you *want* to write in. If it's someone else's, note what you like about it.

If the user has no saved posts, ask them to write each one fresh — even messily, in note form. Their natural wording matters more than polish.

Treat **Sample 3** as the aspirational benchmark — the voice they're moving toward. Treat **Samples 1 and 2** as the baseline — where they are now. The goal is to meet them between both.

**D. Voice fingerprinting**
Once samples are provided, analyse them and summarise back to the user:
- How they open posts (contrast, scene-setting, direct statement, question)
- Sentence rhythm (short & punchy, long & flowing, mixed)
- Connector words they favour (However, But, And, So)
- How they end posts (forward-looking, reflective, simple sign-off)
- Any signature patterns (tagging people, using specific phrases, exclamation mark style)
- What to avoid (things that would sound "not like them")

Ask: "Does this sound right? Anything to add or correct?"

---

## Step 2: Build the Voice Profile

After onboarding, store and use this structure for all future posts:

```
VOICE PROFILE
-------------
Role & audience: [from onboarding]
Tone: [from onboarding]
Post length: [from onboarding]
Emojis: [yes/no + style notes]
Hashtags: [yes/no]

Voice fingerprint:
- How they open: [pattern]
- Sentence rhythm: [pattern]
- Connector words: [list]
- How they end: [pattern]
- Signature patterns: [list]
- What to avoid: [list]

Reference posts: [paste their real samples here]
Clearest rhythm example: [the one sample that best shows their natural voice]
```

---

## Step 3: Drafting Posts

Once the voice profile is established, use this workflow for every post request:

1. **Search for recent news** — Use web search to find a relevant trend or development from the past month connected to the topic. This adds a global perspective without making the post feel like a news article.

2. **Clarify if needed** — If the input is too sparse, ask one question only: "What's the one thing you want the reader to take away?"

3. **Identify the arc** — Hook / Context / What happened + what was learned / Ending

4. **Draft the post** — Match the voice profile exactly. Weave in the news anchor naturally (one sentence is enough). Write in the user's voice, not yours.

5. **Note the news angle** — After the draft, add a brief note in brackets: *[News anchor used: X — please verify or swap if needed]*

6. **Invite feedback** — Ask: "Does this sound like you? Anything to tweak?"

---

## Global Mindset & News Anchoring

Every post should subtly show the user is aware of the wider world, not just their immediate environment.

- Anchor to a **recent trend or news item (less than 1 month old)** relevant to the post topic
- Keep it light — one sentence woven naturally into the post
- Phrase it like: "With [X] making headlines lately..." or "As [trend] continues to gain traction..." or just weave it into the opening
- Topics to watch: AI & tech trends, industry-specific regulatory changes, workplace shifts, regional (APAC/SEA/global) developments

**What to avoid:**
- Sounding like a news anchor or analyst
- More than one external reference per post
- News that feels forced or irrelevant to the personal story

---

## Universal Writing Rules

Regardless of the user's voice profile, always follow these:

- Never start with "I" as the very first word — reframe to a scene, observation, or contrast
- No bullet points or lists in the post — write in prose
- No hollow calls to action ("Drop a comment below!", "What do you think?")
- No inspirational fluff ("Every day is a new opportunity!")
- No AI-sounding phrases ("In today's fast-paced world...", "I'm humbled and grateful...")
- Preserve any phrasing from the user's own draft that already sounds natural — elevate, don't overwrite
- Use placeholder tags like [Name] for people the user may want to tag
- When in doubt, write shorter — restraint reads as confidence

---

## Refinement Loop

After delivering a draft:
- If the user says "not quite like me" — ask what feels off (tone? rhythm? a specific phrase?) and redraft
- If the user rewrites a sentence themselves — treat that rewrite as a new voice signal and update your understanding of their rhythm
- The goal is for the post to pass the "did I write this?" test

