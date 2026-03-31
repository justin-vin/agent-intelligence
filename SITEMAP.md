# Agent Intelligence Microsite — Sitemap

## Structure

```
/                           → What is Agent Intelligence (existing page, refined)
/what-agents-do             → Capability taxonomy — what's actually possible today
/prompting-strategy         → How to talk to agents — patterns that work
/context-engineering        → The thesis: context > model intelligence
/evals                      → Measuring intelligence — baselines, regressions, evidence
/skills                     → Packaged intelligence — recipes, workflows, compound value
/the-stack                  → Deep dive on the four-layer model
```

## Page Summaries

### 1. Home: What is Agent Intelligence
**Status:** Exists (Dom's draft)
**Purpose:** Define the domain. Set the frame.
**Key ideas:** Intelligence as inference layer, the four-layer stack, critical interface, roadmap horizons.
**Refinements:** Light polish. Add nav to other pages. Maybe a "start here" feeling.

### 2. What Agents Can Do
**Purpose:** Ground the abstract in the concrete. A capability taxonomy.
**Key ideas:**
- The current frontier: what agents reliably do today vs. what's emerging vs. what's hype
- Categories: research & synthesis, drafting & editing, data transformation, workflow execution, monitoring & alerting, multi-step reasoning
- The "surprisingly good at" list — things people underestimate
- The "not yet" list — honest about current limits
- How capabilities compound (an agent that can email + calendar + context = meeting prep that actually works)
**Tone:** Practical, grounded, slightly opinionated. Not a feature list — a map of the territory.

### 3. Prompting Strategy
**Purpose:** How to write prompts that produce reliable outcomes. The craft.
**Key ideas:**
- Prompting as programming — deterministic intent, probabilistic execution
- The spectrum: instruction → conversation → collaboration
- Structural patterns: role framing, chain of thought, few-shot, self-critique
- Anti-patterns: over-specification, prompt stuffing, instruction conflicts
- Context window management — what goes in, what stays out, ordering effects
- System prompts vs. user prompts — different jobs, different strategies
- The "teach don't tell" principle — shaping behavior over time vs. per-turn micromanagement
**Tone:** Practitioner-focused. Not "prompt engineering 101" — assumes the reader builds with agents.

### 4. Context Engineering
**Purpose:** The Wordware thesis. Why context is the moat, not model intelligence.
**Key ideas:**
- Intelligence is commoditizing. Context is not.
- What counts as context: memory, tools, files, integrations, preferences, history
- The compounding effect — after 90 days, the agent knows things no fresh session can
- Context as a file system — queryable, structured, evolving
- The window problem: finite tokens, infinite context. What goes in matters more than how smart the model is.
- "Context engineering" as a discipline — who does it, what it looks like, where it's going
- Wordware's position: the world's leading context lab
**Tone:** Thesis-driven, ambitious. This is the big idea page.

### 5. Evals & Measurement
**Purpose:** How to know if intelligence is actually improving. Evidence over vibes.
**Key ideas:**
- Why evals matter: without measurement, every change is a coin flip
- What to measure: decision quality, task completion, faithfulness, user trust signals
- Building baselines: golden sets, regression suites, before/after comparisons
- The observability stack: traces, decision logs, confidence calibration
- A/B testing prompts — not just "which is better" but "better at what"
- The human-in-the-loop eval: user corrections as signal
- Continuous eval vs. point-in-time eval
**Tone:** Rigorous but accessible. Not academic — practitioner-oriented.

### 6. Skills & Recipes
**Purpose:** Packaged intelligence. How skills compound platform value.
**Key ideas:**
- What a skill is: a reusable unit of intelligence + capability
- The skill lifecycle: discover a pattern → package it → ship it → iterate
- Skills as the FTUE lever: out-of-box power that demonstrates value instantly
- Recipe model: do it 2-3x manually → Sauna offers to automate → one-click from then on
- The skill marketplace thesis: community-contributed intelligence
- Skill design principles: composable, testable, context-aware
- Examples: meeting prep, email triage, research synthesis, data cleanup
**Tone:** Product-oriented. Shows how intelligence becomes tangible value.

### 7. The Stack (Deep Dive)
**Purpose:** Expand the four-layer model from the home page.
**Key ideas:**
- Infrastructure: runtime, storage, auth, networking — the floor everything stands on
- Capabilities: the harness. Tool execution, API calls, sandbox, retries, auth flows
- Intelligence: tokens to outcomes. System prompts, reasoning, decision logic, skills
- UX/Product: what users see. The invisible intelligence made visible through design
- The interfaces between layers — where things break and where things shine
- Why this decomposition matters: clear ownership, clear contracts, parallel progress
**Tone:** Architectural. For the team, not just external audience.

## Design Notes
- Match existing aesthetic: Instrument Serif + Inter, cream palette, gear motifs
- Each page: standalone but linked. Read any page solo, or read the whole thing.
- Nav: simple top bar or sidebar. Nothing heavy.
- Responsive. Mobile-first.
- No stock imagery. Diagrams and typography do the work.

## Open Questions
- Audience: internal team? External/public? Both? (Affects depth and tone)
- Should this live on a subdomain (intelligence.sauna.app) or section of main site?
- Do we want interactive elements (e.g., live prompt playground)?
