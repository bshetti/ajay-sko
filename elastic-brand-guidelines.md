# Elastic Brand Guidelines (Reference Document v2)

> **For use with Claude.** Upload this file to any project or conversation to give Claude full Elastic brand context for visual outputs (slides, web pages, documents, dashboards, charts, social graphics) and written content.

> **Source.** Consolidated from the official Elastic Brand Guide at `brand.elastic.co` (cover page + 10 sub-pages: Logo, Colors, Icons, Typography, Illustrations, Photography, Writing style guide, Writing for LLMs, Elky, Motion). Visual assets (logo SVGs, photos, illustration files, animated GIFs) live in the portal — this document captures the rules, specs, and decisions.

---

## Table of contents

1. Logo & wordmark
2. Color system
3. Typography
4. Icons
5. Illustrations
6. Photography
7. Motion
8. Elky (mascot)
9. Writing style guide
10. Writing for LLMs (LLMO)
11. Implementation reference (CSS, React, pptxgenjs, python-pptx, openpyxl)

---

# 1. Logo & wordmark

## What the logo represents

The Elastic logo represents a cluster — a set of connected nodes working together as a single system. It stands for individuals with their own talents and skill sets coming together as one unit.

## Logo variants

| Variant | When to use |
|---|---|
| **Primary logo** (horizontal) | Default. Use unless layout or production constraints prevent it. |
| **Vertical (secondary) logo** | Only for small square spaces. |
| **The cluster (glyph alone)** | Avatars, social profiles, favicons, app install/launch buttons. Not for general logo use. |

## Logo colors

| Name | Hex | RGB | Pantone | CMYK |
|---|---|---|---|---|
| Elastic Blue | `#0B64DD` | 11, 100, 221 | 2387 C | 83, 63, 0, 0 |
| Pink | `#F04E98` | 240, 78, 152 | 2038 C | 0, 84, 3, 0 |
| Yellow | `#FEC514` | 254, 197, 20 | 123 C | 0, 23, 98, 0 |
| Teal | `#02BCB7` | 2, 188, 183 | — | — |
| Lime | `#9ADC30` | 154, 220, 48 | — | — |

> Note: Teal and Lime appear in the logo but are not part of the core brand palette used for general design work.

## Anatomy

The logo has two parts: the **cluster (glyph)** and the **wordmark**. The cluster has a white border that may be invisible on light backgrounds — it is integral and cannot be removed.

## Clear space

Use the cluster shape from the logo as a buffer. Maintain that clear space between the logo and any other graphic element or adjacent logo.

## Things to avoid

- Don't remove the white border from the cluster.
- Don't make all-black or all-white versions. Use the official monochromatic versions instead (available in the brand portal Downloads tab).
- Don't use the logo or cluster as a watermark or faded design element. Always full opacity.
- Don't use AI or design software to alter the logo.
- Don't create new or alternate versions.
- Don't place the logo on visually busy or distracting backgrounds.
- Don't use the cluster as an image mask.
- Don't combine the logo with other shapes or modify it to include them.

## Logo + tagline lockups

The Elastic logo pairs with the **"The Search AI Company"** tagline in approved lockups. Primary, secondary, and centered (video) lockups exist in all-black, all-white, black-with-color-cluster, and white-with-color-cluster variants. Treat these as a rough guide; consult the brand design team for clarity.

## Monochromatic versions

Only use a monochromatic logo when production constraints (one-color print, embroidery, etc.) require it. Available in primary, reverse, vertical, and glyph forms.

## Solutions logos

Light-background and dark-background variants exist for: **Elasticsearch**, **Observability**, **Security**.

## Product feature logos

Light- and dark-background variants exist for: Elastic Stack, Kibana, Beats, Logstash, ECE, Cloud, SIEM, Metrics, APM, Logging, Uptime, Maps, ECK, Endpoint, XDR.

## Partner lockup

A vertical pipe (`|`) symbol separates Elastic's logo from a partner's, signifying collaboration. If partner brand guidelines prohibit the pipe, omit it and use ample space between logos instead.

---

# 2. Color system

## Core colors

| Name | Hex | RGB |
|---|---|---|
| Elastic Blue | `#0B64DD` | 11, 100, 221 |
| Light Teal | `#48EFCF` | 72, 239, 207 |
| Light Poppy | `#FF957D` | 255, 149, 125 |
| Pink | `#F04E98` | 240, 78, 152 |
| Yellow | `#FEC514` | 254, 197, 20 |
| Midnight | `#153385` | 21, 51, 133 |
| Developer Blue | `#101C3F` | 16, 28, 63 |

## Background colors

| Name | Hex | Usage |
|---|---|---|
| Elastic Blue | `#0B64DD` | Primary hero/feature backgrounds, title and closing slides |
| White | `#FFFFFF` | Default content backgrounds |
| Light Gray | `#F5F7FA` | Card fills, icon-circle backgrounds, alternating sections |
| Developer Blue | `#101C3F` | **Card/container outlines only.** Never a slide background. |

## Text colors

| Name | Hex | Usage |
|---|---|---|
| Dark Ink | `#1C1E23` | Primary text on light backgrounds |
| Ink | `#343741` | Body text, secondary text |
| White | `#FFFFFF` | Text on dark or colored backgrounds |

## Greyscale (full ramp)

| Name | Hex |
|---|---|
| White | `#FFFFFF` |
| Light Gray | `#F5F7FA` |
| Medium Gray | `#DCE2EA` |
| Dark Gray | `#ABB4C4` |
| Ink | `#343741` |
| Dark Ink | `#1C1E23` |

## Color ratios (CRITICAL)

The brand specifies how much of each color should appear across visual materials.

### Tier 1 — Dominant (40%)
| Color | Proportion | Role |
|---|---|---|
| Elastic Blue | 20% | Primary brand color: headers, CTAs, hero/feature sections |
| White | 20% | Breathing room, content backgrounds, whitespace |

### Tier 2 — Supporting (36%)
| Color | Proportion | Role |
|---|---|---|
| Developer Blue | 15% | Card/container outlines on content slides only |
| Light Teal | 11% | Primary accent: highlights, success, visual pop |
| Light Gray | 10% | Alternating section backgrounds, cards, dividers |

### Tier 3 — Accent (24%, ~4% each)
| Color | Role |
|---|---|
| Dark Ink | Text only, never a design fill |
| Midnight | Small dark accent moments, not a major background |
| Pink | Badges, tags, secondary highlights |
| Yellow | Warnings, callouts, small emphasis |
| Medium Gray | Borders, subtle dividers, disabled states |
| Light Poppy | Warm highlights, alerts, attention grabbers |

### Proportion rules

1. **Elastic Blue and White share the throne equally** (~20% each). White is intentional design, not just empty space.
2. **Developer Blue is for card outlines only.** 15% means it appears frequently — but exclusively as 1-2px stroke around card/container shapes. Never as a slide background, footer/header bar, divider, or decorative line.
3. **Light Teal is the primary accent.** Reach for it first when you need one accent color.
4. **Light Gray is a major player.** Use it for alternating section backgrounds and card fills.
5. **Midnight is NOT a structural color.** Same weight as Pink or Yellow. No backgrounds.
6. **Tier 3 colors are seasoning.** No accent should fill a large background unless deliberately a single-accent hero moment.

## Expanded illustration palette

Used only for illustrations and motion designs that need additional depth, light, shadow, or gradient. Not for general UI or layout.

| Family | Dark | Mid | Light |
|---|---|---|---|
| Blue | Dark Blue `#0A52B3` | Light Blue `#1893FF` | Sky Blue `#45A8FF` |
| Teal | Dark Teal `#128D91` | Teal `#02BCB7` | (Light Teal `#48EFCF`) |
| Poppy | Dark Poppy `#E55940` | Poppy `#FA744E` | (Light Poppy `#FF957D`) |
| Pink | Dark Pink `#DD0A73` | (Pink `#F04E98`) | Light Pink `#F990C6` |
| Yellow | Dark Yellow `#FFAD18` | (Yellow `#FEC514`) | Light Yellow `#FFDF56` |

## Gradient palette

Gradient combinations are available **only as accents within illustrations** — never as backgrounds.

---

# 3. Typography

## Philosophy

Elastic typography pairs **extra bold headlines with lighter accompanying text**. Titles are short and set in extra-bold weight to anchor messaging. Subheads and body are significantly smaller, creating clear hierarchy.

## Type family

| Font | Use | Availability |
|---|---|---|
| **Mier B Extrabold** | Headlines (external marketing) | Licensed from General Type Studio. Web license + limited desktop seats for the design team. Contact brand team before use. |
| **Inter** (Regular/Bold) | Paragraphs, UI, body text, headlines when Mier B unavailable | Open source ([rsms.me/inter](https://rsms.me/inter), Google Fonts). Also used in Elastic product dashboards. |
| **Space Mono** | Code blocks, large numerals | Open source (Google Fonts). |
| **Space Grotesk** | Developer-specific marketing headlines (more readable than Space Mono) | Open source (Google Fonts). **Brand design team approval required before use.** |

## Fallback chain

For internal documents, PowerPoint, Google Docs/Slides, or emails where Mier B isn't available:
1. **Inter** — primary alternate for everything (headlines + body)
2. **Arial** — last-resort fallback only when Inter isn't available

## Practical font selection

| Context | Headlines | Body | Code/Numbers |
|---|---|---|---|
| External marketing (web, print) | Mier B Extrabold | Inter | Space Mono |
| Developer marketing | Space Grotesk* | Inter | Space Mono |
| Presentations (PPTX, Google Slides) | Inter Bold | Inter Regular | Space Mono |
| Internal documents, emails | Inter Bold | Inter Regular | Space Mono |
| Product UI / Kibana dashboards | Inter | Inter | Space Mono |
| Claude-generated artifacts (HTML/React) | Inter Bold | Inter Regular | Space Mono |

*Requires brand design team approval.

## EUI/Kibana font stack

```
'Inter', BlinkMacSystemFont, Helvetica, Arial, sans-serif
```

## Type hierarchy & spacing

- Establish a comfortable vertical space between headline and paragraph.
- For positioning an eyebrow or CTA, **double** that initial spacing.

## Line-height (Adobe-specific math)

Adobe tools don't accept percentages. Multiply font size by:
- **1.14 (114%)** for headlines
- **1.55 (155%)** for paragraphs

## Color contrast

Type must meet **WCAG AA 4.5:1 contrast ratio** minimum. Verify with a tool like [WebAIM contrast checker](https://webaim.org/resources/contrastchecker/).

| Combination | Pass? |
|---|---|
| Dark Ink / Ink on White or Light Gray | ✅ |
| White on Developer Blue, Midnight, or Elastic Blue | ✅ |
| Dark Ink on Light Teal, Yellow, or Light Poppy | ✅ |
| White on Light Teal, Yellow, or Light Poppy | ❌ insufficient |

## Type rules

- ✅ Adhere to color and line-spacing guidance.
- ❌ Don't use low-contrast text/background combinations.
- ❌ Don't combine various weights of the typefaces together in the same composition.
- ❌ Don't stretch, squash, or distort type.
- ❌ Don't use values outside the documented specs.

---

# 4. Icons

## Marketing vs UI icons

The brand portal icons are **marketing icons** for blogs, decks, and marketing surfaces. **Do not use them as UI icons.** For UI, use Elastic UI Framework's icon library at [eui.elastic.co](https://eui.elastic.co/#/display/icons).

## Two types

**Specific icons.** Designed for a particular product feature, solution, or industry. Use only in that context.

**General icons.** Flexible — use for benefits, value props, broader talking points.

Examples of specific feature icons in the library: add_data, agent, AI, alerting, APM, beats, canvas, cases, cloud, cloud_security, console, crawler, dashboards, discover, ECCTL, ece, eck, ECS, endpoint, ESQL, fleet, ESQL, integrations, kibana, lens, logs, logstash, machine_learning, maps, ML jobs (advanced/multi-metric/population/single-metric), monitoring, notebook, packetbeat, pipeline, reporting, rollups, saved_objects, search_profiler, search_ui, searchable_snapshots, security_analytics, serverless, SIEM, SOAR, spaces, SQL, stack, stack_management, streams_wired, timelion, TSVB, universal_profiling, upgrade_assistant, uptime, users_and_roles, visualizer, winlogbeat, XDR. Each available in color and reverse (dark-background).

---

# 5. Illustrations

## Three illustration types

| Type | Description | Use cases |
|---|---|---|
| **Hero** | Larger, more complex stories; often full-body figures. Communicates without text. | Hero website banners, blog images, ebook covers, marketing assets |
| **Spot** | Single idea or focused narrative. Concise, complements text. | Website, marketing assets |
| **Small** | Versatile, near-icon-like. Fast, digestible. | Carousels, decks, small-format collateral with lots of text |

## Color

Illustrations may use the full **expanded illustration palette** (see Color section above). This includes the dark/light variants of the core colors plus the full greyscale ramp.

## Gradients

Gradient combinations are accents within illustrations only — **never used as backgrounds**.

## Rules

- **Do NOT re-size small illustrations.** They are designed for specific dimensions.
- Match illustration style to surroundings — flat, solid graphic style throughout.
- Both light-background and dark-background (reverse) versions exist for each small illustration.

---

# 6. Photography

## Three traits of a great Elastic photo

| Trait | Description |
|---|---|
| **Candid moments** | Authentic, real, action-oriented. Avoid staged or stiff. Prioritize photos from real, in-person events. |
| **Natural light** | Bright, optimistic, well-lit. Avoid moody, dramatic, artificial, or backlit. No intense lens flares. |
| **Vibrant colors** | Bold colors aligned to the brand palette. Incorporate brand colors via clothing or environment. Avoid desaturation or single-color tone overlay. |

## Three photo types

| Type | Description |
|---|---|
| **People** | Diverse ambassadors. Confident without arrogance, curious, approachable. Range of age, race, ability, culture. Natural environments that reflect the subject's world. |
| **Landscapes & cityscapes** | Expansive, well-composed, beautiful, real. Focused color palette, minimal wide-angle distortion. Leave breathing room for text or illustration overlays. |
| **Photoviz** | Subtle data references woven into photos via repeated elements, patterns, or visual rhythms. Best for executive use cases. |

## Treatments

**Brand cluster overlay.** Place clusters strategically on imagery to enhance flow without obscuring focal points. Apply cluster colors per brand palette guidelines. Rules:
- **Use only white clusters over imagery** for visibility/contrast.
- **Only one cluster per composition** to maintain visual strength.

**UI overlay.** Show illustrated UI mockups against photos to reveal product interaction. UIs can be offset over photo edges or cropped behind people/objects. Use for developer campaigns, web hero banners, social banners.

**Photo frame.** Outlined frame aligns photos with the illustration style. Don't use on small images. Don't over-use (e.g., not on multiple images in a series). Use for website hero/landing images, collateral, brand campaigns.

## Audience guidance

| Audience | Approach |
|---|---|
| **Developers** | Authentic daily-work imagery (remote or in-office). Casual clothing, not buttoned-down. Avoid clichés. Highlight the product. Use Photoviz for technical content. |
| **Decision-makers** | Real-world use cases. Strategic moments, decision-making, collaboration in professional settings. |

## Mood: do / don't

| Do | Don't |
|---|---|
| Approachable, composed, infectious. Confident, comfortable, engaging. | Dreamy, distant. Overwhelmed, distracted, attention elsewhere. |

---

# 7. Motion

## Three principles

**Intentional.** Every transition serves a functional purpose, not decoration. Guide focus, explain hierarchy, confirm actions. Consistent timing and easing make motion predictable.

**Subtle.** Premium polish. Restraint over flair. Don't compete with the message.

**Fluid.** Continuous flow, not disconnected steps. Controlled easing and subtle overlap so as one element exits, another enters seamlessly.

## Easing curves

Three approved curves — do not deviate:
- **Ease in and out**
- **Accelerate**
- **Decelerate**

## Motion rules

- ✅ Keep motion refined, controlled, elegant.
- ❌ No playful or bouncy motion.
- ✅ Use seamless transitions or match cuts.
- ❌ Don't cut abruptly without considering timing and flow.
- ✅ Follow the brand text animation styles.
- ❌ Don't experiment with new text animation styles.

## Logo animation

Use the official animated logo file when bringing the logo onscreen. Available for download in the brand portal.

## UI animation

Keep the interface itself static to preserve clarity and usability. Show real, functional UI — not abstracted or stylized. Use minimal motion cues (arrows, click indicators) to demonstrate interactions. Apply subtle 3D rotation to the overall UI canvas for visual interest without distorting the UI.

## Illustration motion

- **Layering & depth.** Use scale and z-depth so elements feel like they exist in space.
- **Consistency.** Consistent timing, easing, direction. Don't mix many motion styles in one sequence.

## Text animation styles

Five approved styles, all using the approved easing curves:

**Standard:**
- **Scroll up**
- **Push by line**

**Supplemental:**
- **Masking**
- **Flow**
- **Zoom**

## Video elements

- **Title card.** Required for all video productions. Establishes identity and tone.
- **Lower thirds.** Use to introduce speakers (name, role, company).
- **Transitions.** Signal meaningful scene/section changes. Simple cuts often suffice when no shift needs emphasis.

## Caption settings

- **Text:** Inter Regular 48pt, white
- **Background:** `#3F3F3F`, opacity 75%, box size 15

---

# 8. Elky (mascot)

## Identity

Elky is Elastic's official mascot — an elk. Name comes from **ELK Stack** (Elasticsearch, Logstash, Kibana). One Elky exists in Elastic's universe. He may appear with new clothes or accessories to mark acquisitions or product launches, but he remains the same Elky.

## Personality (the four traits)

| Trait | What he does | What he doesn't |
|---|---|---|
| **Infectiously enthusiastic** | Energetically gesticulate | Cause a spectacle |
| **Insatiably curious** | Stop to ask and examine | Live in la-la land |
| **Creatively pragmatic** | Workshop interesting ideas | Elk-splain mad ideas |
| **Lovably unconventional** | Love to dress the part | Live in a costume 24/7 |

Reference vibe: **Mark Rober meets Jony Ive, if Jony Ive were an ace software developer.**

## Two core purposes

1. Promote and embody Elastic's brand personality.
2. Explain complex technical topics and make them easier to understand.

When using Elky, he must serve at least one.

## Where Elky belongs (and doesn't)

| ✅ Use Elky for | ❌ Don't use Elky for |
|---|---|
| Engaging developers (events, swag, dev marketing) | Engaging investors or C-suite prospects/customers |
| Explaining technical concepts | Explaining serious topics (security reports, earnings, company announcements) |
| Internal use (Slack, employee engagement, swag, stickers, milestones) | Pitching Elastic's solutions / sales materials |

## Usage by social channel

| Channel | Elky usage |
|---|---|
| **ITDM content** (corporate) | Low. Moments of levity within a more sober environment. Restraint is key. |
| **Developer content** | Medium. Supporting role — adds clarity, context, simplicity. E.g., animated overlay in technical videos ("Decoded with Elky"), leaning on a code block in X posts, CTAs on LinkedIn. |
| **Employer Brand content** | High. Most creative freedom. Can appear in real-life photographic settings (composited intentionally, full scale, never with drop shadows or 3D reflections — he stays flat/graphic). |

## How Elky communicates

- **Elky does not speak with sound.** No video or audio applications where he is audibly speaking.
- He communicates through writing + body language + facial expressions.
- His thoughts are connected to his face by a simple line with a gentle arc and a small gap. Line should match the weight and color of his facial features.
- Thought text uses **Space Grotesk Medium**, in **Dark Ink** (`#1C1E23`), always center-justified.

## Elky's tone of voice

| Trait | Description |
|---|---|
| **Confident, but not authoritative** | Calm, steady. Reassures through clarity and experience, doesn't rush to prove expertise. |
| **Approachable, but not sales-y** | Welcoming, accessible. Doesn't assume prior expertise. Genuinely enthusiastic without being smarmy. |
| **Thoughtful, but not pedantic** | Conversational warmth. Adapts to context. Acknowledges nuance. Never formulaic. |
| **Technical, but not a know-it-all** | Embraces complexity but makes it accessible. Knows when simplicity matters. Meets people where they are. |

### Voice examples

| ✅ Do | ❌ Don't |
|---|---|
| "The quickest way to approach this is to check your cluster health first." | "We recommend leveraging cross-functional synergies to optimize your observability framework." |
| "Hey, good to see you again. What are we debugging today?" | "Welcome back! Kindly clarify what your issue is below and we'll do our very best to find a solution." |
| "Hmm, interesting. Are you sorting on a text field by any chance?" | "You're so right. That's a really wonderful insight." |
| "An index template is basically a blueprint — if the blueprint is off, the structure follows." | "You need to reconfigure the JVM heap sizing parameters in conjunction with the GC algorithm…" |

## Visual style

- **Bipedal.** Elky never walks on all fours. Always closer to a human than a real elk.
- **Slim, human-like body** built from simple geometric shapes.
- **Only one Elky at a time** in any composition.
- Subtle imperfections (sharp-edged strokes, slightly offset hooves) are part of the character.

## Proportions

Use the height of Elky's head as the unit for measuring the rest of his body. Maintain proportions across digital, print, and motion.

## Linework

| Element | Line weight |
|---|---|
| Facial features (eyebrows, eyes, mouth) | **1x** (never varies) |
| Antlers | **2x** (always twice as thick as other linework) |
| Definition lines (separating limbs/body) | **1x** |

When resizing, convert strokes to outlines, use Figma's Scale (K), or Illustrator's "include strokes" setting to preserve proportions.

## Color rules for Elky

- A simple shadow appears at his feet whenever full body is shown.
- **Black and Elky Orange are reserved for Elky only.** Don't use these colors anywhere else in the marketing design system.
- Do **not** place Elky on Yellow or Light Poppy backgrounds (visibility issue).
- No gradients, highlights, or patterns. No new colors, shading, or textures.
- No alternate colors or shading treatments to create stylistic Elky variations.

## Expression

Lead emotion with **ears and eyebrows**. Higher ears = excitement; lower ears = calm focus. Always optimistic and approachable — never negative, aggressive, or cynical.

## Production guidance for swag

- Default to full character in full color palette.
- Constrained spaces (small patches, lapel pins, structured hats): use approved silhouette, head-only, or single-color treatment.
- Stickers: include a white expanded safe zone. No full-bleed sticker treatments.
- **Stuffed toys:** Use only preapproved vendors. Contact the Elastic Swag Program manager for vendor info.
- All public-facing Elky usage must be approved by Elastic's Brand team.

---

# 9. Writing style guide

## Style basics

- **Default to American English** (`realize`, not `realise`). Switch to regional spelling for region-specific content.
- **Sentence-style capitalization** for titles, headings, subheadings, menus, buttons. Exception: published report titles use title case (e.g., *Global Threat Report*).
- **Oxford (serial) comma** by default. Omit for regions where it's nonstandard.
- **One space after a period.** No space between numbers and units (`100GB`, not `100 GB`).
- For grammar/punctuation not covered, refer to the **Chicago Manual of Style**.
- For terms not covered in the glossary, refer to **Merriam-Webster**.

## Reading level target

Aim for **reading level 10 or below** for brand and digital content. Tools like the Hemingway App help. Use plain language, short sentences, fewer adjectives/adverbs.

## Dashes

- **Em dash** (—) for breaking thoughts inside a sentence. **One space on each side.** Also for quote attribution.
- **En dash** (–) for numeric ranges not preceded by *from*/*between* (e.g., `June 18–19`). No spaces.
- Don't use two hyphens (`--`) for an em dash.

> Note: Mike's personal authorial voice avoids em dashes entirely (uses commas, periods, or colons instead). Apply this preference for Mike's drafts; Elastic marketing content otherwise follows the brand rule above.

## Numbers

- Spell out zero through nine. Numerals for 10+. Exception: titles/headlines always use numerals.
- Spell out numbers at the start of a sentence (except years).
- **Percentages.** Use `%` symbol with numerals; spell out *percent* if the number is spelled out. For ranges: `30%–50%` (en dash, % on both sides).
- **Large numbers.** Avoid `M` or `mil` abbreviations in headlines, descriptions, presentations, full sentences. Write `$1 million`, `$20 billion`.
- **Currency.** Use `$` alone when context is clear. When it isn't: `US$3,000`, `C$3,000`, `A$3,000`.

## Date and time

- Standalone (heading, blog timestamp): `12 August 2020` (day/month/year).
- Running text: `August 12, 2020` (month day, year). Switch to regional convention for region-specific content.
- Avoid abbreviating months with numbers.
- Day abbreviations: Mon, Tue, Wed, Thu, Fri, Sat, Sun.
- `a.m.` / `p.m.` (lowercase, periods, space before): `6:00 a.m.`
- Default to 12-hour clock; switch for region-specific content.

## Job titles

**In a sentence:** Lowercase except proper nouns. Exception: capitalize when it precedes the person's name (use sparingly, senior leadership only).
> "It's important to tailor your resume," says Charlie White, senior recruiter at Elastic.
> Elastic Founder and CTO Shay Banon is the creator of Elasticsearch.

**Stand-alone (quote attribution, presenter list):** Capitalize. Person's name first, then role, then company. Use commas, not "at" or "of".
> — Ash Kulkarni, CEO, Elastic

Always abbreviate VP, SVP, CEO, CFO, HR. Spell out Junior/Senior (no Jr./Sr.).

## Pronouns

- Use **singular "it"** for companies, not plural "they" (`Google released its update`, not `their`).
- For tutorials, "we" can make writing more conversational ("First, we're going to set up…"). Don't overuse. Default to imperative ("First, set up…").

## Other conventions

- **Ampersands.** Don't use `&` to replace "and" in a sentence. OK in tight character contexts (social posts, headlines, designed materials). Never put a comma immediately before an ampersand.
- **Bullets.** Periods at end if items are complete sentences (or two+ sentences). No punctuation for short fragments. Capitalize first letter. Parallel construction (all fragments or all sentences, not mixed).
- **Colons.** Lowercase first word after, unless it's a proper noun, complete sentence, quotation, question, or first word in a title.
- **Comma splices.** Don't use them. Break into two sentences, add a conjunction, or use a semicolon or em dash.
- **e.g. / i.e.** Avoid. Prefer "for example," "such as," "like" / "that is." If you must use, only inside parentheses with the expected punctuation.
- **etc.** Avoid. Prefer "such as" or "like" + examples. Never use both *etc.* and *such as*/*like* in the same sentence.
- **Quotation marks.** Periods and commas inside. Colons and semicolons outside. Question/exclamation marks outside unless part of the quoted material.
- **versus.** Spell it out in sentences. `vs.` (with period) only in space-constrained contexts (tables, headlines).

## Footnotes & citations

- Numbers, not symbols. Superscript in text, full-size in the footnote at end of document.
- No space before footnote number in running text.
- After a comma/period/question mark/colon/semicolon/parenthesis/quote: number goes immediately after the punctuation. After a dash: number comes before the dash.
- Citations include: author/organization, title, month + year. Hyperlink on the source name for digital sources.

## Hyphenation

- Hyphenate two+ words that jointly modify another word (`real-time search`). Don't hyphenate when it's a noun or adverb (`search in real time`).
- Don't hyphenate "very" or `-ly` adverbs (`highly popular packages`).
- Generally no hyphen for prefixes `semi`, `pre`, `non`, `un`, `sub`, `multi`. **Do** hyphenate after a prefix + proper noun, and for `all-`, `ex-` (former), `mid-`, `self-`. Also when prefix's last letter matches root's first letter (`sub-bucket`, `re-enable`).

## Term glossary (selected — full list in brand portal)

### Product & feature names

**Use:**
- **Elasticsearch** (not "Elastic Search" or "Elastic Enterprise Search")
- **the Elasticsearch Platform** (not "Search AI Platform" — phased out). "the" is lowercase except at start of sentence/title.
- **Elastic Cloud**, **Elastic Cloud Enterprise (ECE)**, **Elastic Cloud Hosted (ECH)**, **Elastic Cloud on Kubernetes (ECK)**, **Elastic Cloud Serverless**
- **Elastic Stack** (formerly ELK Stack — only use "ELK Stack" for audiences more familiar with that name)
- **Elastic Observability**, **Elastic Security**
- **Elastic Security for endpoint** (not "Elastic Endpoint Security")
- **Kibana**, **Kibana Lens** (Kibana can be omitted after first use)
- **Beats** (singular when product offering: "Beats 5.0 is great"; plural when referring to multiple: "Beats are lightweight shippers")
- **Logstash**, **Fleet**, **Canvas** (not "Elastic Canvas" or "Kibana Canvas")
- **Elastic Agent** in full or "the agent" (lowercase). Never "Agent" alone.
- **Elastic Agent Builder** (full first reference, then "Agent Builder"). Not "Elastic's Agent Builder" or "Elastic AI Agent Builder."
- **Elastic AI Assistant**, **Elastic AI Assistant for Observability**, **Elastic AI Assistant for Security** (not "Observability/Security AI Assistant")
- **Elastic Workflows** (singular). Capitalize "Workflows" when referring to the feature; lowercase when referring to specific workflows.
- **Streams** (singular, capitalized for the feature; lowercase for specific streams). Not "Elastic Streams."
- **Significant Events** (singular, capitalized for feature). Not "Elastic Significant Events."
- **Search AI** (S always capitalized). Don't use "search-powered AI."
- **the Search AI Company** ("the" lowercase except at start of sentence or standalone use like the homepage)
- **ES|QL** (Elasticsearch Query Language)
- **KQL** (Kibana Query Language), **EQL** (Event Query Language)
- **ELSER** (Elastic Learned Sparse EncodeR)
- **BBQ** (Better Binary Quantization)
- **logsdb index mode** (always lowercase "logsdb" except at start of sentence). Not "LogsDB."
- **Universal Profiling**, **Stack Monitoring**, **Search UI** (not "Elastic Search UI")

**Phased out — do not use:** App Search, Site Search, Workplace Search, Elastic Search, Elastic Enterprise Search, ESS, Elastic Endpoint Security, Search AI Platform.

### People-related

- **Elasticians** for Elastic employees. **Don't** use "head" or "headcount" for Elastic employees.
- **distributed**, not "remote," when describing how Elasticians work.
- **Spaces** (capitalized for the Kibana feature; lowercase for specific spaces).
- **Discuss** (capitalized when referring to Elastic's community site).

### Acronyms (don't need definition on first use)

AI, API, AWS, CPU, GA, GB, Gb, GCP, GDPR, IT, InfoSec, ISV, JSON, LDAP, SQL ("an SQL database", pronounced "ess-que-ell"), GenAI, IIoT, IoT.

### Compound words

- **backend** (adj), **back end** (noun)
- **backup** (noun), **back up** (verb)
- **drill down** (verb), **drilldown** (noun)
- **dropdown**
- **end-user** (adj), **end user** (noun)
- **follow-up** (adj/noun), **follow up** (verb)
- **frontend** (adj), **front end** (noun)
- **login** (noun), **log in** (verb), **log in to**
- **meetup** (noun), **meet up** (verb)
- **on-prem, on-premises** (never "on-premise")
- **on-site** (adj), **on site** (adverb)
- **real time** (adverb), **real-time** (adj)
- **roll up** (verb), **rollup** (noun: rollup API, rollup index, rollup job)
- **set-up** (adj), **setup** (noun), **set up** (verb)
- **signup** (noun), **sign up** (verb)
- **timeout** (noun), **time out** (verb)
- **up-to-date** (adj), **up to date** (not modifier)

### Other terms

- **24/7** (with slashes)
- **agentic AI**, **AI agent(s)**
- **Agent / agent.** Capitalized for specific agent (Elastic Agent); lowercase for general (APM agents).
- **C-suite**, **DevOps**, **DevSecOps**
- **canceling, canceled, cancellation** (single L except "cancellation" with two)
- **cloud native** (hyphenate as modifier: "cloud-native workloads")
- **cloud connected** (lowercase), **Cloud Connect** (capitalized for the product)
- **codebase**, **lifecycle**, **dataset**, **datastore**, **data center**, **database**, **data lake**, **data source**
- **data** is singular
- **ebook**, **ecommerce**, **elearning**, **email**, **internet**, **online**
- **home page**, **web page**, **website**, **web crawler**, **white paper**, **whitespace**
- **OK** (not "okay")
- **OpenTelemetry (OTel)**
- **open source** (don't hyphenate; capitalize only when referring to the Open Source Initiative)
- **out-of-the-box** (adj), **out of the box** (adverb), **OOTB**
- **time series** (never hyphenated)
- **time frame**, **timeline**, **multi-cloud**, **multitenancy**, **multitenant**, **multifactor**, **multifields**
- **n-gram** (always lowercase n)
- **Wi-Fi**, **Node.js**, **Kubernetes (K8s)**, **Painless**
- **Zero Trust** (capitalized)
- **MITRE ATT&CK** (follow MITRE's guidelines)
- **machine learning (ML).** Don't abbreviate when referring to "Elastic machine learning features."
- **main menu** for Kibana top-level navigation. Don't use "side navigation," "sidebar," "navigation bar," "side nav," "left-hand nav," "toolbar."
- **navigation menu** for Elastic Cloud's primary menu. Same prohibitions as above.
- **subscription** lowercase. **Standard, Gold, Platinum, Enterprise subscriptions** are capitalized.
- **Kibana Spaces** is the feature; lowercase "spaces" for specific spaces.
- **Real User Monitoring (RUM)** capitalized when formal feature name; lowercase otherwise.

### Avoid these words

- **leverage** → use *use*
- **utilize** → use *use*
- **world-class** → explain why instead
- **sexy** → never use
- **hack** in the "tips and tricks" sense (e.g., "Top 10 Kibana hacks")
- **signal** in security context → use *alert* (detection alert, Kibana alert)
- **disabled** to refer to inactive user/account
- **DNT** as abbreviation for designated node type
- **head**, **headcount** for Elastic employees
- **big data** when you can be specific (e.g., "tens of petabytes")

---

# 10. Writing for LLMs (LLMO)

## Why this matters

AI answer engines (ChatGPT, Claude, Perplexity, Gemini, Google AI Overview) are reshaping discovery. The role of brand/product websites is shifting from "displaying information aligned to keywords" to "educating the engine's knowledge graph." The goal is to be embedded in the LLM's knowledge graph over time, and in the shorter term, ensure brand-relevant content is easy for AI engines to retrieve and cite.

## Five C's of LLM-friendly content

| Principle | What it means |
|---|---|
| **Clarity** | Simple, direct language; clear headings; well-organized topics. Both humans and machines should easily interpret. |
| **Contextual relevance** | Anticipate the *why* and *how* behind a query, not just the *what*. |
| **Credibility** | Author expertise, citations, quotes, original data, transparent sourcing. |
| **Structure & schema** | Schema markup, clear metadata, semantic structure, robots.txt. |
| **Consistency** | Quality and accuracy across all topics. Trains engines to trust the domain. Keep messaging current. |

## Best practices by element

### Meta titles & H1s
- One clear topic per page.
- Concise, descriptive, specific.
- Avoid broad, generic, or duplicate titles.

### Introductory paragraph
- Above-the-fold content is heavily weighted.
- State what the reader will learn or accomplish.
- Plain, declarative language. Main topic terms naturally.
- Don't bury the core idea.

### Body copy
- Directly related to the H1.
- Clear, concise, factual, accurate, consistent across Elastic properties.
- Logical sections. Lists, bullets, visuals, short paragraphs.
- No duplicate content.

### Subheadings
- H2 for major themes, H3 for subtopics.
- Each section answers one question.
- Avoid vague headings ("Overview," "Features").
- Treat each section as self-contained — models retrieve chunks, not pages.

### Writing for skim & parse
- Short paragraphs (1–3 sentences).
- Front-load key points.
- Bullets, numbered steps, tables where they aid scanning.
- Define acronyms on first mention.
- Active voice, direct phrasing ("X does Y").

### Linking
- Internal links power topic understanding.
- Descriptive anchor text (name the concept, not "click here").
- Fix broken links.

### Authority signals
- Reference reputable orgs (MITRE, NIST, CNCF) where relevant.
- Primary sources, original data.

### Media
- Images that support the narrative, not decorative.
- Descriptive alt text — short, purpose-focused.
- Reference visuals in the body ("see diagram below").
- Don't embed critical text inside images without describing it in surrounding text.
- Video captions and transcripts.

### Maintenance
- Review for accuracy regularly.
- Version markers where relevant.
- Update internal links.
- Use redirects for moved/merged pages.

## LLMO checklist

**Headings:** One clear H1; descriptive; logical hierarchy (H2 → H3 → H4); no styling-only headings.

**Intro paragraph:** First 1–3 sentences summarize purpose; states what reader will learn; plain language.

**Body:** Single idea per section; product terminology accurate; lists/callouts/short paragraphs for scannability; examples or visuals; no duplication; objective, factual tone.

**Readability:** Declarative sentences; short paragraphs; logical flow; explicit statements ("Elastic supports X"); self-contained sections.

**Lists:** Parallel and concise; lead-in introduces purpose; not overly long or nested.

**Links:** Descriptive anchor text; relevant; reliable; no broken links; support narrative.

**Multimedia:** Visuals support content (not decorative); high-quality, unique; concise alt text; videos captioned/transcribed.

**URLs:** Match topic, short, descriptive, hyphens, lowercase; matches H1.

**Maintenance:** Reviewed regularly; current product names; legacy references removed; change log updated; redirects in place.

---

# 11. Implementation reference

## CSS Variables

```css
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Space+Mono&family=Space+Grotesk:wght@400;500;600;700&display=swap');

:root {
  /* Core */
  --elastic-blue: #0B64DD;
  --light-teal: #48EFCF;
  --light-poppy: #FF957D;
  --pink: #F04E98;
  --yellow: #FEC514;
  --midnight: #153385;
  --developer-blue: #101C3F;

  /* Backgrounds & text */
  --dark-ink: #1C1E23;
  --ink: #343741;
  --light-gray: #F5F7FA;
  --medium-gray: #DCE2EA;
  --dark-gray: #ABB4C4;
  --white: #FFFFFF;

  /* Expanded illustration palette */
  --dark-blue: #0A52B3;
  --light-blue: #1893FF;
  --sky-blue: #45A8FF;
  --dark-teal: #128D91;
  --teal: #02BCB7;
  --dark-poppy: #E55940;
  --poppy: #FA744E;
  --dark-pink: #DD0A73;
  --light-pink: #F990C6;
  --dark-yellow: #FFAD18;
  --light-yellow: #FFDF56;

  /* Type */
  --font-headline: 'Inter', Arial, sans-serif;
  --font-body: 'Inter', Arial, sans-serif;
  --font-code: 'Space Mono', monospace;
  --font-dev-headline: 'Space Grotesk', 'Inter', sans-serif;
}
```

## React / Tailwind config

```js
const colors = {
  elasticBlue: '#0B64DD',
  lightTeal: '#48EFCF',
  lightPoppy: '#FF957D',
  pink: '#F04E98',
  yellow: '#FEC514',
  midnight: '#153385',
  developerBlue: '#101C3F',
  darkInk: '#1C1E23',
  ink: '#343741',
  lightGray: '#F5F7FA',
  mediumGray: '#DCE2EA',
  darkGray: '#ABB4C4',
};

const fonts = {
  headline: "'Inter', Arial, sans-serif",
  body: "'Inter', Arial, sans-serif",
  code: "'Space Mono', monospace",
  devHeadline: "'Space Grotesk', 'Inter', sans-serif",
};
```

In the artifact's `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Space+Mono&family=Space+Grotesk:wght@400;700&display=swap" rel="stylesheet" />
```

## pptxgenjs (Node.js)

```js
const C = {
  elasticBlue: "0B64DD",
  lightTeal:   "48EFCF",
  lightPoppy:  "FF957D",
  pink:        "F04E98",
  yellow:      "FEC514",
  midnight:    "153385",
  devBlue:     "101C3F",
  darkInk:     "1C1E23",
  ink:         "343741",
  lightGray:   "F5F7FA",
  white:       "FFFFFF",
};

const FONT = {
  headline: "Inter",      // Mier B unavailable outside design team
  body:     "Inter",
  code:     "Space Mono",
};

// Title/closing slide background
slide.background = { color: C.elasticBlue };

// Teal accent rule under a header (key brand pattern)
slide.addShape(pres.shapes.RECTANGLE, {
  x: xPos, y: yPos, w: 1.0, h: 0.035,
  fill: { color: C.lightTeal }
});

// Card outline (Developer Blue stroke, not filled)
slide.addShape(pres.shapes.ROUNDED_RECTANGLE, {
  x: 1, y: 2, w: 4, h: 2,
  fill: { color: C.white },
  line: { color: C.devBlue, width: 1.5 },
  rectRadius: 0.12
});
```

## python-pptx

```python
from pptx.dml.color import RGBColor

ELASTIC_BLUE   = RGBColor(0x0B, 0x64, 0xDD)
LIGHT_TEAL     = RGBColor(0x48, 0xEF, 0xCF)
LIGHT_POPPY    = RGBColor(0xFF, 0x95, 0x7D)
PINK           = RGBColor(0xF0, 0x4E, 0x98)
YELLOW         = RGBColor(0xFE, 0xC5, 0x14)
MIDNIGHT       = RGBColor(0x15, 0x33, 0x85)
DEVELOPER_BLUE = RGBColor(0x10, 0x1C, 0x3F)
DARK_INK       = RGBColor(0x1C, 0x1E, 0x23)
INK            = RGBColor(0x34, 0x37, 0x41)
LIGHT_GRAY     = RGBColor(0xF5, 0xF7, 0xFA)
WHITE          = RGBColor(0xFF, 0xFF, 0xFF)
```

## openpyxl

```python
from openpyxl.styles import PatternFill, Font

ELASTIC_BLUE_FILL = PatternFill(start_color="0B64DD", end_color="0B64DD", fill_type="solid")
HEADER_FONT = Font(color="FFFFFF", bold=True, size=12)
```

---

## Quick-Start Prompt for Claude

When starting a new conversation, paste with the file:

> "I've attached the Elastic brand guidelines. For all visual outputs (slides, web pages, documents, charts), follow the color palette, color proportions, typography rules, and color-application-by-context guidance. Use Inter for type unless I specify otherwise. Developer Blue is for card outlines only, never for backgrounds or decorative shapes. For written content, follow the Elastic writing style guide — sentence-case headings, Oxford comma, US English, target reading level 10 or below, and use the official term glossary. Don't use Elky in executive, sales, or formal materials."

---

*End of document.*
