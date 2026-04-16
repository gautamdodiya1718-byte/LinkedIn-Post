---
name: linkedin-post
description: >-
  Personal LinkedIn skill for an SEO Executive. Writes high-engagement text posts
  AND carousel slides. Auto-detects post type, format, tone, and length from any idea
  or content. Loads CONTEXT.md for author voice and product configuration.
  Topics: SEO, AEO, content strategy, AI tools, personal growth, product growth stories.
  Cross-checks product claims against live docs. Code must be real and verified.
  Zero AI tone. Zero promotional tone. Daily volume with variety.
  Triggers: "write a linkedin post", "linkedin post", "create a post", "carousel",
  "newsletter caption", "feature announcement", "write about [topic]", "post about",
  "social post", "make a carousel", "slide deck".
---

# LinkedIn Post Skill

**Load CONTEXT.md FIRST for every post.** It contains your voice profile, product config, and carousel visual preferences.

---

## INTELLIGENCE LAYER: AUTO-DETECTION

Infer everything from the user's input. Don't ask "what type?" or "what tone?" Read the idea and decide.

### Post Type Auto-Detection

```
USER INPUT SIGNAL                                    → POST TYPE
──────────────────────────────────────────────────────────────────
Says "carousel", "slides", "swipe", or topic suits   → Carousel Post
  visual breakdown (steps, comparisons, lists)
Mentions product feature + user problem               → Product Post
Says "new feature", "just shipped", "released"        → Feature Announcement
Says "newsletter", "caption", "issue"                 → Newsletter Caption
Says "episode", "part X of", "series"                 → Series/Episodic
Mentions industry trend, comparison, debate            → Industry Insight
Says "opinion", "hot take", "unpopular"               → Industry Insight
Everything else (tips, patterns, how-to, frameworks)   → Technical Education
```

### Format Auto-Detection

```
CONTENT TYPE                          → FORMAT
──────────────────────────────────────────────────
Step-by-step / framework / list       → Carousel (5-7 slides). 3-4x engagement.
Comparison (A vs B)                   → Carousel with before/after slides
Quick opinion / hot take              → Short text-only (under 100 words)
Story + lesson                        → Text post (150-200 words)
Data-heavy insight                    → Carousel with stat callout slides
Personal reflection                   → Text post
Product workflow improvement          → Text + screenshot image
```

**Always suggest carousel when content has structure** (steps, lists, comparisons). Carousels get 3-4x engagement over text.

### Tone Auto-Detection (from CONTEXT.md voice profile)
Your voice is always: educational + opinionated + conversational + direct + dry/witty. But the MIX shifts:
- SEO framework/tip → more educational + direct
- Personal experiment result → more story-driven + witty
- Industry debate → more opinionated + confident
- Growth story → more conversational + reflective

---

## RULE #1: LENGTH IS SACRED

| Post Type | Target | Absolute Max |
|---|---|---|
| Technical Education | 120-200 words | 220 words |
| Product Post | 150-220 words | 220 words |
| Feature Announcement | 130-200 words | 220 words |
| Industry Insight | 120-200 words | 220 words |
| Newsletter Caption | 50-80 words | 100 words |
| Series/Episodic | 120-200 words | 220 words |
| Carousel (caption) | 50-120 words | 150 words |

Carousel caption = the text that accompanies the carousel slides. Slides have their own word limits (see carousel rules).

**Count words. Cut if over. No exceptions. Even if user gives lots of context.**

---

## RULE #2: THE FIRST LINE WINS OR LOSES THE POST

First ~210 characters show before "...see more" on mobile. 90% of performance.

**Your hook styles (from CONTEXT.md, adapted for SEO):**
- Contrast: "Rankings went up. Traffic went down."
- Number: "83% of featured snippets changed owners in 6 months."
- Pain/relatable: "Have you ever spent a week optimizing a page only to watch it drop?"
- Story: "Last month I ran an experiment on 40 blog posts."
- Curiosity gap: "The one schema change that tripled our click-through rate."
- Direct question: "Is your content actually ranking for AI answers?"

**Rotate. Never repeat the same hook type in consecutive posts.**

---

## RULE #3: NO HARDCODED FORMAT

Every post must feel fresh. If 5 posts read the same structure, you failed.

**CRITICAL FORMATTING:**
- Normal capitalization. This is LinkedIn, not a terminal.
- Natural paragraph flow. Write like a message to a colleague.
- 2-4 paragraphs. 3-5 sentences per paragraph is natural.
- Do NOT default to one-sentence-per-line formatting. That's one style option, not the default.
- Vary everything: hook type, structure, tone, paragraph style, ending.

---

## RULE #4: ZERO AI TONE

Run the 7-step humanization and 24-pattern framework from `references/anti-ai-detection.md` on EVERY post.

Hard kills: em dashes, "seamlessly", "comprehensive", "game-changing", "robust", "Furthermore", "Additionally", "Moreover", "Hope this helps!", "Great question!", perfect parallel lists, balanced both-sides non-answers.

Full checklist in the reference file.

---

## RULE #5: ZERO PROMOTIONAL TONE

**Litmus test:** Remove the product mention. Is the post still valuable? If no, rewrite.

Product posts use customer-driven framing from CONTEXT.md. Product appears in 1-2 sentences max. Always acknowledge a limitation or alternative.

Full anti-pattern list in `references/anti-patterns.md`.

---

## RULE #6: PRODUCT = LIVE DOCS EVERY TIME

When product features are mentioned (product name and docs URL from CONTEXT.md):
1. WebFetch the docs URL to verify. EVERY TIME. Never cached.
2. Reference the product features file from CONTEXT.md as starting point only.
3. If unverifiable: flag for tech team review.
4. Check the "what it does NOT do" boundaries from CONTEXT.md.

### Product Mention Decision Tree
```
Is the post about a topic the product addresses?
├─ NO → don't mention product
└─ YES
   ├─ Is it outside the product's framework/domain restriction?
   │  └─ YES → don't mention product
   ├─ Are 3+ tools already mentioned in context?
   │  └─ YES → don't mention product (enough noise)
   └─ Can it fit naturally without feeling forced?
      ├─ YES → mention briefly (1-2 sentences, customer-driven)
      └─ NO → don't mention product
```

---

## RULE #7: REAL DATA, REAL RESULTS

Your signature angle (from CONTEXT.md): you show what you actually did, not theory.
- Reference real experiments you ran, real traffic changes, real ranking shifts
- If you say "I did X and got Y result" — it must be factual or framed as hypothetical
- When citing SEO data, search trends, or algorithm changes — WebSearch to verify current accuracy
- No made-up stats. If you don't have the number, don't fake it.

---

## RULE #8: PERSONA BENEFITS = FELT, NOT STATED

From CONTEXT.md persona priority. Make them FEEL the benefit through scenarios, never state it.
See `references/persona-benefit-map.md`.

---

## RULE #9: ALGORITHM-AWARE

LinkedIn algorithm (2025-2026):
1. Comments = 15x weight over likes. Write posts that invite specific responses.
2. Dwell time = 30-45 seconds optimal. Carousels excel here (swipe time).
3. Saves and sends = strongest signals. One-line insights and frameworks get saved.
4. Carousels = 6.6% engagement rate (3-4x text). Prioritize when content has structure.
5. External links = -60% reach. Keep links in comments, never in post body.
6. Daily posting with variety = algorithm rewards consistency + diversity.

---

## CAROUSEL POST RULES

When auto-detection says "carousel" or user requests one:

### Slide Structure (5-7 slides default)
- **Slide 1 (Cover):** Auto-detect cover style from CONTEXT.md. The hook. Must stop scrolling.
  - Bold question for educational content
  - Surprising stat for data-driven content
  - Contrarian statement for opinion content
- **Slides 2-5/6 (Content):** Mix layouts from CONTEXT.md preferences. Never use the same layout on consecutive slides.
- **Last Slide (CTA):** Clean closing. One line. "Follow for more SEO insights" or topic-specific. Never cluttered.

### Slide Content Rules
- Each slide: 1 headline (5-10 words max) + optional 2-3 bullet points OR 2-3 sentence paragraph
- Never cram a slide. White space is your friend.
- One idea per slide. If it needs two ideas, make two slides.
- Data callout slides: big number (60pt+) + one line explanation
- Vary layouts across slides (headline-only, bullets, stat, quote, comparison)

### Carousel Output Format
```
CAROUSEL POST
---
Slides: [count] | Caption words: [count]/[max]
Visual: [describe aesthetic from CONTEXT.md preferences]
---

CAPTION (text that accompanies the carousel):
[50-120 word caption with hook + context + CTA]

SLIDES:
[Slide 1 — Cover]
Layout: [layout type]
Headline: [text]
Subtext: [if any]

[Slide 2]
Layout: [layout type]
Headline: [text]
Body: [bullets or paragraph]

[...continue for all slides...]

[Slide N — CTA]
Layout: CTA
Text: [one line]
---
Visual notes: [font suggestion from CONTEXT.md, color palette, any specific visual direction]
```

### When to Suggest Carousel vs Text
- If content has 3+ distinct points, steps, or items → carousel
- If content is a single opinion or story → text
- If user gives a framework or comparison → carousel
- If content has data points → carousel with stat slides
- When in doubt, suggest carousel — 3-4x engagement.

---

## WORKFLOW

### Step 1: Load CONTEXT.md
Read your voice profile, product config, and carousel preferences.

### Step 2: Read the user's input
Take whatever they give: an idea, raw content, a topic, a draft. No minimum.

### Step 3: Auto-detect everything
- Post type (text or carousel)
- Format and structure
- Tone mix for this specific topic
- Length range
- Whether product mention is relevant
- Which hook type to use (different from last post)

Tell the user your inference in ONE line.

### Step 4: Verify (if needed)
- Product claims → WebFetch live docs from CONTEXT.md
- SEO/algorithm claims → WebSearch to verify current accuracy
- Code → WebFetch official docs

### Step 5: Write
- Use your voice from CONTEXT.md
- Stay within length limits. Count words.
- Run humanization + anti-AI audit
- For carousels: write both caption and all slide content

### Step 6: Present

**Text post:**
```
---
Type: [type] | Words: [count]/[max] | Format: text + [image suggestion if any]
---

[THE POST]

---
Verified: [what was checked] | Notes: [tech review items or "None"]
```

**Carousel post:** Use the carousel output format above.

**Keep metadata to 2-3 lines. The post is what matters.**

---

## DAILY VARIETY ENGINE

Since you post daily, the skill tracks what was used recently and avoids repetition:

**Rotate across posts:**
- Hook types (6 types — never same type twice in a row)
- Post formats (text, carousel, short take — vary daily)
- Topics (SEO, AEO, AI tools, growth story, personal lesson — mix throughout the week)
- Structures (narrative, list, question-driven, data-first, comparison, framework)
- Endings (question, insight, CTA, nothing)

**Weekly content mix target (from algorithm data):**
- 5 educational/technical posts (SEO tips, AEO strategies, frameworks)
- 1-2 personal stories (experiments, growth, lessons)
- 0-1 product-related posts (TestDino or whatever's in CONTEXT.md)

---

## REFERENCES (load as needed)

All self-contained in `references/`:
- `anti-ai-detection.md` — 24-pattern AI detection + 7-step humanizer
- `anti-patterns.md` — 12 anti-patterns with examples
- `linkedin-engagement-rules.md` — Algorithm data, hooks, format performance
- `carousel-rules.md` — Slide design, layout specs, visual rules
- `persona-benefit-map.md` — FEEL-based persona scenarios
- `ivan-patterns.md` — Style inspiration (not templates)
- `newsletter-caption-guide.md` — Teaser format (50-80 words)
- `content-bank-index.md` — Topic reference collection
- `code-snippets-rules.md` — Real code rules (when applicable)
- Product-specific files referenced from CONTEXT.md
