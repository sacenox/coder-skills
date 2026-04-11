# Research Notes for `human-writing`

This file captures the research basis behind the skill. Keep the
main `SKILL.md` practical; keep detailed evidence here.

## Wikipedia article and source

### Wikipedia: Signs of AI writing
Source page:
- https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing
- Source wikitext: https://en.wikipedia.org/w/index.php?title=Wikipedia:Signs_of_AI_writing&action=raw

Key takeaways used in the skill:
- The page treats AI tells as **patterns**, not proof. A single word or
  one awkward sentence is not enough.
- Many strong tells are about **generic significance claims**,
  **superficial analysis**, **promotional wording**, **vague
  attribution**, and **rigid essay structure**.
- It flags repeated "AI vocabulary" clusters such as `additionally`,
  `align with`, `delve`, `underscore`, `pivotal`, `vibrant`,
  `showcase`, and `tapestry`.
- It highlights broader structural habits: rule-of-three phrasing,
  overused em dashes, Markdown-heavy output, canned collaborative
  phrasing, and generic "challenges / future outlook" conclusions.
- It also includes a useful warning section on **ineffective
  indicators**: blandness, transition words in isolation, and formal
  prose are not reliable proof by themselves.

How it shaped the skill:
- Focus on removing formulaic phrasing and generic uplift, not on
  banning individual words absolutely.
- Emphasize specificity, judgment, and natural rhythm over detector
  gaming.
- Add boundaries so the skill does not encourage false claims of human
  authorship.

## Research on distinctive AI style

### Russell, Karpinska, Iyyer (ACL 2025)
Source: https://aclanthology.org/2025.acl-long.267/

Why it matters:
- Frequent ChatGPT users were strong detectors of AI-generated text and
  outperformed many automated detectors.
- Their explanations relied not just on word lists, but also on
  **formality, originality, and clarity**.

How it shaped the skill:
- The skill focuses on overall feel and judgment, not only lexical
  substitutions.
- "Human" writing should sound selective and situated, not just less
  detectable.

### Juzek and Ward (COLING 2025)
Source: https://aclanthology.org/2025.coling-main.426/

Why it matters:
- Documents lexical overrepresentation in LLM writing, with words such
  as `delve`, `intricate`, and `underscore` appearing far more often
  after LLM adoption.
- Treats this as a measurable linguistic drift, not just a meme.

How it shaped the skill:
- Include a short watchlist of repeated AI-favorite wording.
- Frame the issue as **clusters and repetition**, not one forbidden
  token.

### Kobak et al. (Science Advances 2025)
Source: https://www.science.org/doi/10.1126/sciadv.adt3813

Why it matters:
- Shows abrupt post-2022 increases in excess vocabulary across more
  than 15 million biomedical abstracts.
- Reinforces that LLM writing leaves a measurable lexical footprint at
  scale.

How it shaped the skill:
- Prefer plain verbs and concrete nouns over polished but generic
  vocabulary.
- Warn against abstract noun piles and repetitive stylistic markers.

### Rudnicka (Scientific American, 2025)
Source: https://www.scientificamerican.com/article/chatgpt-and-gemini-ai-have-uniquely-different-writing-styles

Why it matters:
- Argues that major chatbots have distinct **idiolects**, much like
  humans do.
- Implies that AI tells shift over time and differ by model.

How it shaped the skill:
- Avoid hard-coded, forever bans.
- Teach broader habits: specificity, rhythm, audience matching, and
  selective judgment.

### Saha and Feizi (2025)
Source: https://arxiv.org/abs/2502.15666

Why it matters:
- Detectors often flag even lightly AI-polished human text as AI.
- This creates false accusations and shows the limits of detector-first
  thinking.

How it shaped the skill:
- Optimize for better writing, not for beating detectors.
- Keep the skill centered on readable, honest prose.

## Official style guidance on sounding human without sounding sloppy

### Google developer documentation style guide - Voice and tone
Source: https://developers.google.com/style/tone

Key takeaways used in the skill:
- Aim for a voice that is conversational, friendly, respectful, and
  natural.
- Sound like a **knowledgeable friend**, not a pedant and not a clown.
- Avoid buzzwords, placeholder phrases, choppy repetition, and
  long-winded sentences.

### Digital.gov - Plain Language Web Writing Tips
Source: https://digital.gov/resources/plain-language-web-writing-tips

Key takeaways used in the skill:
- Get to the point quickly.
- Use contractions, active voice, familiar words, and short paragraphs.
- Put the most important information first.

### 18F Content Guide - Be concise
Source: https://guides.18f.gov/content-guide/our-approach/be-concise/

Key takeaways used in the skill:
- Be specific, informative, brisk, and human.
- Use contractions and short sentences.
- Vary sentence length so writing stays readable without sounding
  robotic or clipped.
- Avoid adjective-heavy spin and caveat-bloated grammar.

## Practical synthesis

Across the sources, the same advice keeps showing up:

1. Lead with the point.
2. Prefer concrete nouns and verbs over abstract uplift.
3. Use contractions when natural.
4. Vary sentence rhythm.
5. Match the audience's register.
6. Avoid repeated formulae, hype, and canned summaries.
7. Keep clarity and honesty above "sounding human".
