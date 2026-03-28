# 🎨 AI4Change Brand Guidelines

These guidelines ensure a consistent, recognizable identity across all AI4Change communications, code, and community interactions.

---

## Color Palette

### Primary Colors

| Color | Name | Hex | Usage |
|:-----:|:-----|:----|:------|
| 🟩 | **Emerald Teal** | `#00D4AA` | Primary brand color — CTAs, links, highlights, active states |
| 🟪 | **Electric Violet** | `#7C3AED` | Secondary — accents, badges, community elements |
| 🟧 | **Warm Coral** | `#FF6B35` | Accent — alerts, urgency, problem submissions |
| ⬛ | **Deep Space** | `#0A0E1A` | Dark backgrounds, text on light backgrounds |

### Extended Palette

| Color | Name | Hex | Usage |
|:-----:|:-----|:----|:------|
| ⬜ | **Cloud White** | `#F8FAFC` | Light backgrounds, cards |
| 🔘 | **Slate** | `#64748B` | Secondary text, muted elements |
| 🟩 | **Teal Light** | `#CCFBF1` | Success states, subtle highlights |
| 🟪 | **Violet Light** | `#EDE9FE` | Subtle accents, tag backgrounds |
| 🟧 | **Coral Light** | `#FFF7ED` | Warning states, notification backgrounds |

### Color Ratios

- **60%** Deep Space / Cloud White (background)
- **25%** Emerald Teal (primary actions, key UI)
- **10%** Electric Violet (accent, secondary actions)
- **5%** Warm Coral (highlights, urgency)

### Accessibility

All color combinations must meet **WCAG AA** contrast minimums:
- `#00D4AA` on `#0A0E1A` — ✅ 9.2:1 (AAA)
- `#F8FAFC` on `#0A0E1A` — ✅ 18.1:1 (AAA)
- `#FF6B35` on `#0A0E1A` — ✅ 6.1:1 (AA)
- `#7C3AED` on `#F8FAFC` — ✅ 5.4:1 (AA)

---

## Typography

### Font Stack

| Role | Font | Weight | Fallback |
|:-----|:-----|:-------|:---------|
| **Headlines** | [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) | 700 (Bold), 500 (Medium) | `system-ui, sans-serif` |
| **Body** | [Inter](https://fonts.google.com/specimen/Inter) | 400 (Regular), 500 (Medium), 600 (SemiBold) | `system-ui, sans-serif` |
| **Code** | [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) | 400 (Regular) | `monospace` |

### Type Scale

| Element | Size | Weight | Font |
|:--------|:-----|:-------|:-----|
| Hero Title | 48px / 3rem | 700 | Space Grotesk |
| Section Heading (H2) | 32px / 2rem | 700 | Space Grotesk |
| Sub-heading (H3) | 24px / 1.5rem | 500 | Space Grotesk |
| Body | 16px / 1rem | 400 | Inter |
| Small / Caption | 14px / 0.875rem | 400 | Inter |
| Code | 14px / 0.875rem | 400 | JetBrains Mono |

### Line Heights

- Headlines: 1.2
- Body text: 1.6
- Code blocks: 1.5

---

## Logo

### Current State

> 🚧 The AI4Change logo is currently in development. The guidelines below will apply once the logo is finalized.

### Planned Usage Rules

- **Minimum clear space**: 1x the height of the logo mark on all sides
- **Minimum size**: 32px height for digital, 12mm for print
- **Preferred placement**: Top-left for headers, centered for hero sections
- **Color variants**: Full color, monochrome white (on dark), monochrome dark (on light)

### What NOT to Do

- Don't stretch, rotate, or distort the logo
- Don't place the logo on busy or low-contrast backgrounds
- Don't add effects (drop shadows, gradients, outlines)
- Don't recreate or modify the logo — use official assets only

---

## Tone of Voice

### Core Principles

| Principle | What It Means |
|:----------|:-------------|
| **Inspiring but grounded** | We paint a vision, then show the concrete steps to get there |
| **Technical but accessible** | We speak to developers without alienating non-technical contributors |
| **Global but personal** | We address a worldwide audience while making each person feel seen |
| **Confident but humble** | We believe in our mission without pretending we have all the answers |
| **Action-oriented** | Every communication should make the reader want to *do* something |

### Writing Style

- **Use active voice**: "We build solutions" not "Solutions are built"
- **Be direct**: Lead with the point, not the context
- **Use "we" and "you"**: Create a sense of shared ownership
- **Prefer short sentences**: If it needs a semicolon, it might need to be two sentences
- **Use concrete examples**: "A farmer in Kenya" not "people in developing nations"

### Do's and Don'ts

#### ✅ Do

- Use real-world examples and specific people/places
- Reference Playing for Change parallels when introducing the concept
- Use the "song" metaphor for solutions/projects
- Include calls to action — always give the reader a next step
- Celebrate contributors and communities
- Use emoji sparingly and purposefully (in headers, status indicators)

#### ❌ Don't

- Use corporate jargon ("leverage," "synergize," "disrupt")
- Talk down to non-technical people
- Make promises we can't keep ("AI will solve poverty")
- Use fear, guilt, or urgency as motivation
- Center ourselves — center the communities and contributors
- Over-use buzzwords ("democratize AI," "paradigm shift")
- Use AI-generated filler or generic motivational language

### Example Copy

> **Good**: "A retired teacher in rural India is using AI to build a literacy tool for her village. She doesn't have a computer science degree. She has 30 years of experience knowing exactly what her students need."
>
> **Bad**: "AI4Change leverages cutting-edge artificial intelligence to democratize technology solutions for underserved communities across the global south."

---

## Imagery

### Photography & Illustration Style

- **Real people in real places** — not stock photos of diverse people high-fiving
- **Working, building, discussing** — action over posed
- **Show the environment** — the farm, the classroom, the street corner
- **Natural lighting** — warm, authentic, not overly processed

### Icons & Graphics

- Use simple, line-based icons
- Match the brand color palette
- Prefer open-source icon sets (Lucide, Heroicons, Phosphor)
- Keep illustrations minimal and purposeful

---

## GitHub-Specific

### Repository Badges

Use flat-square style badges with brand colors:

```markdown
![Badge](https://img.shields.io/badge/Label-Text-00D4AA?style=flat-square)
```

### Issue Labels

| Label | Color | Purpose |
|:------|:------|:--------|
| `problem` | `#FF6B35` | Community-submitted problems |
| `solution` | `#00D4AA` | Active solution development |
| `discussion` | `#7C3AED` | Needs community input |
| `good first issue` | `#CCFBF1` | Welcoming to newcomers |
| `documentation` | `#64748B` | Docs improvements |

---

*These guidelines are living documents. As AI4Change grows, so will our brand. Suggest changes via [Discussions](https://github.com/orgs/ai4change-org/discussions).*
