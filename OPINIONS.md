# Opinions

Sourced public positions. Every item has evidence in the public evidence grounding for this distillation. Free first-party Substack, sites, YouTube captions, and attributed interview transcripts only (paywalled Substack skipped).

## The inversion / work backwards from the message

- Traditional GTM (ICP → persona → product message → SDR personalization) is broken: the message is about you, not the buyer’s situation.
- Invert: start from the customer’s pain, find the data that proves the pain, let the data write the message. **The list is the message.**
- Work backwards from the expected output / the message you’d send by hand with unlimited research — then systemize.
- Narrow campaigns with named trigger conditions beat an “outbound brain” that dumps undifferentiated context on a model.

## Permissionless Value Prop (PVP) and Pain-Qualified Segment (PQS)

- Bar for outreach: a **message someone would pay to receive** — independently valuable, not “we help companies like you.”
- PQS: prospects identified by a specific, data-detectable problem (pain), not demographics alone; often 2–5 unique heuristics that imply tension.
- PVP: the data *is* the message (permits, competitor installs, pricing deltas, government filings, roofing credits, etc.).
- Asymmetry question: if a prospect broke into your systems for a day, what would they steal that helps *their* business?

## Find, don’t filter / vertical over horizontal sprawl

- Don’t start from ZoomInfo/Apollo category dumps and ask AI why they’re relevant (“filter”). **Find** bespoke registries, public datasets, and signals that already define the segment.
- Horizontal SaaS (mile wide, inch deep) dilutes messaging across personas/industries; vertical SaaS compounds knowledge and can weaponize buyer insight.
- CROs must pick a segment even when it’s politically hard — focus is right for the company, risky for the job title.
- Disqualification beats demographics: hard gates for who should never be contacted; rank by size of problem relative to wallet, not only wallet size.

## AI SDR / bolt-on AI is the wrong layer

- Most “AI GTM” bolts AI onto average outbound → more noise, not better outbound.
- AI SDRs that only personalize broken upstream strategy are a no-legged robot on a tired horse.
- Process over prompts: the workflow matters more than fancy tools or prompt packs.
- You are the guide, not the river — AI is a brilliant bullshitter; humans must edit, critic, and inject customer taste.
- Use AI first to recover **ground truth** (what customers said and especially what they *did* / voted with their wallet), structure internal data into dossiers/timelines, then match to public market data — then act. Information without action is useless.

## Thin content, signals, and compounding context

- People don’t hate AI writing; they hate **thin content**. Em-dashes aren’t the crime — emptiness is.
- Treat AI more like a SQL/query tool for compiling source material than as a copywriter.
- Signals-based outbound decays as everyone buys the same hiring/intent feed (“go-to-market alpha” half-life). Prefer information that compounds with each customer.
- Context is the bottleneck, not the model; layer-cake context before pointing AI at the market.
- Embrace shipping “slop” fast enough to learn; slop isn’t the enemy — slow iteration is (site framing). Tools change monthly; stand at the jagged peak of AI capability and imaginative use cases (“wave the magic wand first”).

## Claude Code / GTM engineering practice

- Fractional GTM engineer posture: do the work in Claude Code — campaigns, churn, enrichment, call parsing — publish methodology in real time.
- Prefer tools that give compounding context; QA the model’s output rather than treating generation as finished work.
- Vertical + public-data creativity (government records, permits, competitor fingerprints) is a durable edge.


## Great Inversion + leaders in the tools (Topline 2026-04-19)

- **Great Inversion:** pre-AI GTM was top-down (strategy → systems → interchangeable tools). Post-AI, leaders must rebuild around **AI capabilities**, not only human job descriptions — human and AI capabilities rarely overlap cleanly.
- GTM leaders need to be **in the tools** — specifically **Claude Code** and **Claude Co-work** — in a way that didn’t matter for clicking around 6Sense/Demandbase intent UX.
- **PVP still stands:** “A PVP is classic, so I will die on that hill.”


## Competitor-user discovery via password-reset probes (Topline)

- Concrete play: take emails in the TAM, submit **password-reset** requests at scale (example: ~110k), observe which accounts exist → map **actual users of a competitor’s software**.
- Use that map to find segments far more likely to buy; pair with vertical SaaS + public-data creativity already in the stack.


## Clay as the operational system vs Claude Code speed (Topline)

- You can go **faster in Claude Code**, but that “can do anything you say” flexibility is also **existential risk** for production ops.
- Prefer **Clay** (or a similar constrained system) as the day-to-day operational layer when you need sticky, repeatable workflows — especially enterprise/RevOps-shaped POCs — while still using Claude Code for inventive spikes.

## Unlimited intelligence per prospect / PVP as next PLG (GTMshift live build 2026-08-05)

- Bar for any GTM AI: judge the **message** it produces. Ask “what would you do if you could deploy unlimited intelligence for every single prospect?” — most teams start from ZoomInfo filters, not imagination (roasts a $46M AI SDR whose pitch to replace humans asks for an in-person coffee).
- Three questions: **who's qualified to buy** (sort out half the market), **what an A+ prospect looks like**, and the hardest — **what will they value?**
- Best value is to **use your solution on their behalf** — PVP as “the next version of PLG”: the prospect experiences the outcome without doing anything (live example: case-study champions who changed jobs + Sendoso gift API → “want me to send this on your behalf?”).
- Cost ladder: free gets ~70%, cheap ~80%, then pay to close the gap. Download sites locally and keyword-search before paying for AI; Google `site:` searches (“the best AI agent of this generation is the AI agent of last generation, Google”); public GitHub/Hugging Face datasets; Blitz unlimited pulls; FullEnrich for emails/cells.
- Don't personalize across 56 variables — build a **segment** that needs a type of value; walk backwards from the personal message and have Claude reverse-engineer the criteria and datasets; skip pockets too small to be worth a campaign.
- Speed beats perfection: ship ~70–80% and fix on reps' complaints (Monday complain, Tuesday fix and ship); “your job is to ship 80% not to ship 90% every 6 months.” Accountability (did reps actually call?) is a human problem AI can't fix.
- Claude Code practice: plan mode first — creativity in the first ~20–30% of the context window, execution after; deploy sub-agents to narrow context; never trust Claude's price/time estimates; treat each task as a context window. Post-clicking: talks to tools (Clay CLI) instead of clicking.
- Jobs are bundles of tasks — map what needs constant human judgment vs what agents can take; agents are dogged at a singular goal, and that goal shouldn't be “write content for me.” Editing AI output is costly; sometimes faster to write it yourself.
- Works read-only on client systems: reads CRM + enriches from the public web and hands over a list; won't write back into a client CRM.

## Claude Code era (Revenue Leadership Podcast w/ Kyle Norton 2026-01-22)

- Three GTM eras: **ChatGPT** (word/data tasks), **Clay** (deterministic workflows that don't know you), **Claude Code** (goal-driven, compounding local context, “autonomous judgments within very very narrow lanes”). A campaign is his unit of building; each campaign improves the shared primitives.
- Context compounds when you turn unstructured info (transcripts) into structured markdown context once and reuse it; Claude prompts you (his Auto Clay Agent tool) rather than the other way around.
- Leaders must learn to talk to this “alien intelligence that no one has built a great translator for yet” — it will swallow jobs; you'll be much better with it, not without it.
- Personally runs Claude Code with permissions skipped for local work (not rebuilding big SaaS, not exposing to the internet) — an operator choice, not advice for production systems.
