# Hacker News — Pre-Written Comment Responses

Prepared responses for likely questions and criticisms on HN. Adapt tone to the specific commenter — always genuine, never defensive.

---

## "This is just another feel-good project that won't ship"

You might be right — and that's why we're structured as continuous open source, not a hackathon. If we don't ship, we've failed publicly. The roadmap has concrete milestones: 10 seed problems by end of Phase 1, community vote on the first pilot by May, v1.0 of the first solution by July.

We're also documenting the entire process — wins and failures. If the model doesn't work, at least the postmortem will be useful.

The honest answer: we don't know if this works yet. That's what Phase 1 is for.

---

## "Why not just contribute to existing projects?"

Great question. We're not building a platform — we're building a community-driven pipeline from problem to solution.

If an existing project already solves a community-submitted problem, we'll absolutely contribute there instead of reinventing. The goal isn't to create new repos for the sake of it — it's to ensure real problems get matched with real solutions, whether that's a new project or contribution to an existing one.

---

## "The Playing for Change analogy doesn't hold"

Fair pushback. The analogy isn't perfect — music has a natural mixdown point that code doesn't, and asynchronous collaboration on software is a solved problem in ways music composition isn't.

What we're borrowing is the principle: real people, distributed globally, each contributing their part, composing into something none could build alone. And critically: starting with the people who have something to express (musicians/communities), not starting with a studio (tech company) looking for content (problems).

---

## "How is this different from [X]?" (generic)

Genuinely curious — can you share a link? We've researched DataKind, Code for America, Omdena, DrivenData, and a few others. Here's where we think we differ:

1. Problem-first: Communities submit problems, not organizations or sponsors
2. Continuous: Not event-based or challenge-based
3. AI-as-instrument: AI is the multiplier, not the subject of study
4. Storytelling-as-infrastructure: We document the journey, not just the output
5. Zero barrier: GitHub account and willingness, no application process

But we're early enough to be wrong about what makes us different. If there's significant overlap with X, we'd rather collaborate than compete.

---

## "This needs a business model to be sustainable"

We're exploring grants and sponsorships, but the core constraint is: solutions must be open source and free. We'd rather stay small and open than scale and close.

Long-term options we're considering:
- Foundation grants (Ford Foundation, Mozilla Foundation, etc.)
- GitHub Sponsors
- Corporate sponsorship (for infrastructure costs, not governance influence)
- University partnerships (students contributing for credit)

But honestly, the first priority is proving the model works with one shipped project. Sustainability planning is Phase 4.

---

## "AI solutionism — you're just throwing AI at problems that don't need it"

This is a risk we take seriously. Every project starts with the problem, not the technology. The community vets whether AI is genuinely the right tool. If the best solution doesn't need AI, that's fine too.

The "AI" in AI4Change is about using the most powerful tool currently available as a multiplier. If that multiplier doesn't apply to a specific problem, we won't force it. Pragmatism over ideology.

We explicitly chose "AI as instrument" framing to avoid this trap — an instrument is something you use when the song calls for it, not something you shoehorn into every performance.

---

## "How do you prevent this from becoming just another Western savior project?"

This is probably the most important question we'll face.

The structural answer: problems come from communities, not from us. We don't decide what matters. The people who live the problem decide. The governance model transitions to an elected community council.

The honest answer: this risk is real and we need to actively guard against it. Specific mitigations:
- Problem submissions require context about who submitted and why
- Domain experts and people with lived experience are prioritized in project teams
- Solutions are tested by the communities they serve, not just by developers
- We're actively seeking contributors from Global South communities, not as beneficiaries but as co-builders

We won't get this right immediately. But we're aware of the trap and building structures to avoid it.

---

## "What's the tech stack?"

Intentionally minimal for the org layer:
- GitHub Issues for problem submission
- GitHub Discussions for community
- GitHub Pages (static site) for the website
- GitHub Actions for any automation

Each pilot project will choose its own stack based on problem requirements. We expect common themes:
- Edge deployment / offline-first (many target users lack reliable internet)
- Mobile-first or SMS-compatible (low-resource hardware)
- Open-source ML frameworks (HuggingFace, ONNX, TFLite for on-device)
- Low compute requirements (solutions need to run without GPUs)

---

## "I've seen this idea before and it never works"

We've seen some fail too. From what we can tell, the common failure modes are:

1. **Event-based** (hackathons): Energy dissipates after the event
2. **Top-down**: Someone in San Francisco decides what rural Kenya needs
3. **No community**: Build it and hope they come
4. **Unsustainable**: Dependent on a single funder or maintainer
5. **No storytelling**: Ships a tool, nobody knows it exists

Our structural bets against each:
1. Continuous, not event-based
2. Problem-first from communities, not organizations
3. Community building is Phase 2, before building Phase 3
4. Open governance, multiple funding sources planned
5. Storytelling is core infrastructure, not an afterthought

We could still fail. But at least we'll fail differently than the others.

---

## "Can I help? / How do I get involved?"

The most impactful thing right now: submit a problem. We need real problems from people who live them. If you know someone in agriculture, education, health, or disaster response — ask them what keeps them up at night.

Beyond that:
- Star the repo to signal interest
- Join GitHub Discussions to shape the direction
- Share with communities that might benefit
- If you have domain expertise, we'd love your perspective on submitted problems

GitHub: https://github.com/ai4change-org
Problems: https://github.com/ai4change-org/problems/issues/new
Discussions: https://github.com/orgs/ai4change-org/discussions

---

## "What happens when you get your first problem and nobody builds it?"

Valid concern. This is why we're investing in community building before we attempt the first pilot. The sequence is:

1. Collect 50+ problems (build a backlog worth choosing from)
2. Grow to 25+ engaged contributors (build a team before picking a project)
3. Community vote (democratic selection = buy-in)
4. Clear project charter with milestones (structure, not just enthusiasm)
5. Document everything (accountability through transparency)

If nobody builds the first problem, we'll write an honest postmortem about why and try again with a different approach. The worst outcome is silently dying — we'd rather fail loud and learn.
