# Carousel Post Rules

Self-contained rules for generating LinkedIn carousel slide content and visual specifications. Loads visual preferences from CONTEXT.md.

---

## WHEN TO MAKE A CAROUSEL

Carousels get 3-4x engagement over text posts. Suggest one whenever:
- Content has 3+ distinct points, steps, or items
- Content is a framework, checklist, or methodology
- Content compares two things (before/after, tool A vs B, old way vs new way)
- Content has data points worth visualizing
- Content is a step-by-step process
- User explicitly asks for carousel/slides

**When NOT to carousel:**
- Single opinion or hot take (text is better)
- Short personal story (text is more intimate)
- Quick reaction to news (text is faster)

---

## SLIDE STRUCTURE

### Default: 5-7 Slides

| Slide | Purpose | Layout Options |
|---|---|---|
| 1 (Cover) | Stop scrolling. THE hook. | Bold question, surprising stat, or contrarian claim |
| 2-5/6 (Content) | Deliver value. One idea per slide. | Mix layouts (never same layout twice in a row) |
| Last (CTA) | Clean close. One line. | "Follow for more [topic]" or topic-specific nudge |

### Auto-Adjust Slide Count
- Simple tip (3 points) → 5 slides (cover + 3 content + CTA)
- Framework (5-6 steps) → 7 slides (cover + 5 content + CTA)
- Never exceed 10 slides. Cut ruthlessly.

---

## COVER SLIDE (Slide 1)

The cover IS the hook. On LinkedIn, the cover slide thumbnail is all people see while scrolling.

### Cover Style Auto-Detection
- **Educational content** → Bold question headline
  - "Is your content actually ranking for AI answers?"
  - "What happens when Google's AI writes your featured snippet?"
- **Data-driven content** → Surprising stat
  - "83% of featured snippets changed owners in 6 months"
  - "40 blog posts. One experiment. Here's what I found."
- **Opinion content** → Contrarian claim
  - "Keyword research is dead. Here's what replaced it."
  - "Your SEO strategy is optimizing for the wrong search engine."

### Cover Rules
- Headline: 5-12 words. Must create curiosity or tension.
- Optional subtext: 1 line max (author name, topic label)
- Never cram the cover. Huge text + white space = scroll-stopper.
- Text should take up 40-60% of the slide area.

---

## CONTENT SLIDES (Slides 2 through N-1)

### Layout Options (Mix Across Slides)

**1. Headline + Bullets**
```
Headline: [5-8 words, bold]
• [Point 1 — one line]
• [Point 2 — one line]
• [Point 3 — one line]
```

**2. Bold Headline Only**
```
[One big statement, 6-12 words]
[Takes up full slide. No body text.]
```

**3. Headline + Short Paragraph**
```
Headline: [5-8 words]
Body: [2-3 sentences. Natural prose. Not bullets.]
```

**4. Number/Icon + Label (Infographic Style)**
```
[Big number: 83%]
[One line: "of featured snippets changed owners in 6 months"]
```

**5. Quote Card**
```
"[Quote text — 1-2 sentences]"
— [Source or context]
```

**6. Before/After or Comparison**
```
BEFORE: [old way — 2-3 words or one line]
AFTER: [new way — 2-3 words or one line]
[Optional: one line explaining the shift]
```

**7. Step + Insight**
```
Step [N]:
[Insight headline — 5-8 words]
[1-2 sentence explanation]
```

**8. Data Callout**
```
[BIG NUMBER or STAT]
[One line context/explanation]
```

### Content Slide Rules
- **One idea per slide.** If it needs two ideas, split into two slides.
- **Never cram.** White space makes content readable when swiping.
- **Vary layouts.** Never use the same layout on 2 consecutive slides.
- **Keep text short:** Headlines 5-12 words. Body max 3 sentences. Bullets max 3 items.
- **Be specific.** "Reduced crawl budget waste by 60%" not "Improved SEO performance."

---

## CTA SLIDE (Last Slide)

- One line. Clean. Not cluttered.
- Match the post's topic: "Follow for more SEO experiments" not generic "Follow me"
- Optional: your name/handle for attribution
- Never promotional. Never "Visit our website" or "Try [product] free"

---

## CAPTION (Text Accompanying the Carousel)

The caption is the text post that appears ABOVE the carousel. It's separate from the slides.

### Caption Rules
- 50-120 words. Max 150.
- Hook line first (same rules as text post hooks)
- 1-2 sentences of context about what the carousel covers
- Optional: end with a question to drive comments
- Optional: 1 CTA line (save/follow)
- 1-2 hashtags max at the end

### Caption Structure
```
[Hook line — creates curiosity about the carousel content]

[1-2 sentences: what this carousel covers and why it matters]

[Optional: specific question for comments]

#Hashtag1 #Hashtag2
```

---

## VISUAL SPECIFICATIONS

Load visual preferences from CONTEXT.md. Default specs:

### Color Palettes (Rotate)
- **Clean:** White background (#FFFFFF) + dark text (#1A1A1A) + one accent (blue #2563EB or teal #0D9488)
- **Gradient:** Cool tones — slide backgrounds with subtle blue-to-purple or teal-to-blue gradient
- **High contrast:** Black (#0A0A0A) background + white text + one accent color for emphasis
- **Muted:** Off-white (#F5F5F0) + warm grey text (#4A4A4A) + soft accent
- **Two-tone:** Split slide with brand color on one half, white on the other

### Typography
- **Heading fonts:** Sora, Outfit, Clash Display, DM Sans, Bricolage Grotesque, Plus Jakarta Sans
- Pick ONE heading font per carousel (consistency within a single carousel)
- Rotate fonts across different carousels for variety
- **Body font:** DM Sans or Plus Jakarta Sans
- **Heading size:** Large/bold. 40-60% of slide space for headline-only slides.
- **Body size:** Comfortable reading. Never smaller than 16pt equivalent.

### Layout Principles
- Generous margins (10-15% of slide dimensions on each side)
- Text alignment: left-aligned for body, centered for headlines and stats
- Maximum 3 colors per carousel (background, text, accent)
- Icons: simple line icons only, no clip art, no stock illustrations

---

## OUTPUT FORMAT

```
CAROUSEL POST
---
Slides: [count] | Caption: [word count]/150 | Palette: [which one]
Font: [heading font] + [body font]
---

CAPTION:
[The text post that accompanies the carousel]

SLIDES:

[Slide 1 — Cover]
Layout: [type]
Headline: "[text]"
Subtext: "[if any]"
Visual: [color/style notes]

[Slide 2]
Layout: [type]
Headline: "[text]"
Body: "[content]"

[...each slide...]

[Slide N — CTA]
Layout: CTA
Text: "[one line]"

---
Verified: [what was checked] | Notes: [if any]
```
