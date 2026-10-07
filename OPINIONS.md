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

## Dual Brain — Claude Code and Codex hand each other work (Substack 2026-10-05)

- Stop being the human clipboard between two agents: “I was the slowest part of the system.” Built **Dual Brain** so “one writes, the other checks it blind, and the answer comes back in a format the first one can trust.” Three jobs: **blind review**, **second opinion**, **delegate**.
- Route by strengths and cost: Codex is cheaper on usage (on the bake-off day Claude hit its session limit twice while “Codex ran 977 worker jobs that same day, and none of them hit a usage limit”); in his experience Claude Code handles images better.
- Coordination rules from the build: **one writer per file**; a status format that separates “it ran” from “it worked”; adversarial/devil's-advocate agents catch flaws before you act (“Two agents arguing saved me from putting $10,000 behind a hunch”).
- Be honest about measurement vs product: three days of tests improved “the measurement… and the product hadn't” — carve out the one piece that survives and ship that.
- Writing rule stays: “I tell the story, and the agents fill in what happened” — an AI-first draft that “didn't sound like me” doesn't ship.

## Internal compass / founder story beats AI personalization (own channel, GuJ4SCoLTIU)

- Most prospecting messages amount to “I love your wallet” — about the sender, not the buyer; they miss “the thing that is un-AI-able”: the sender's own internal compass and lived experience.
- Founder sales works “because the founder tells their story” — align your compass with the market's language and problems, then every message is grounded in that connection. Empathy is “hard to fake, but easy to feel”; if it isn't true, “they will sniff it out.”
- **Target by situation, not by signal, because signals are selfish.** AI personalization at scale is “built on a fiction of ZoomInfo filters and industries and head count”; AI “can scale the garbage” but can also synthesize information to boost empathy.

## Information asymmetry / go narrow before you build (FullEnrich podcast 2026-08-06)

- Good GTM comes from information asymmetry: with 50–1,000 customers “you should know more about the 1,001 customer than that customer knows about their own reality.”
- Start from who already bought, why, and who gets outsized value; build customer dossiers from everything they said and did; target who has the worst version of the problem — then “the message is just a re-descriptioning of the targeting.”
- Pre-data founders: “go talk with 100 plumbers and pay them if you have to” before building. “If go to market is hard for you, you're too wide.” Vertical knowledge compounds; “With most horizontal go-to-market, your knowledge fractures.”
- Data sourcing: work backwards from known-good customer records to the public sources that hold them, then build forward — “the models do exceptionally well when they're working backwards from known examples.” Record yourself researching leads manually so Claude can abstract the steps.
- Stack (mid-2026): Claude Code plus trusted APIs; “I'll never use Claude or OpenAI's models for doing search” — uses Exa, Parallel and the Clay agent for agentic search; Blitz for unlimited profile pulls; FullEnrich for contact data (discloses he is an investor/advisor there and a user); Open Web Ninja. Not tool-loyal: “I always use the best tool for the job.” Clay caught on because builders “could showcase our imagination” in it.
- Product: Edge Co-Pilot — “Jordan in your terminal” — sells his knowledge and skills rather than standalone software (for now).

## Paid events as a quality filter (own channel, DIGq6uRgvns, ~2026-10-05)

- Charges for in-person events on purpose: free sponsor events fill seats with “talking heads that don't actually do work”; price keeps the room homogeneous in the work people do. “The person that comes in thinking about a discount is not the person that I want at the event.” Community businesses dilute as they widen.

## GTM engineering vs RevOps / the AI-savvy CRO (The GTMshift podcast, 2026-08-18)

Guest interview (host labeled; Jordan's answers are first-person Blueprint). Caption wording approximate.

- **Data moat, not tools:** buying Clay because someone said so is tool thinking; the real need is a moat, and for GTM the best moat is a data moat — bespoke data that today only lives in SDR/AE research. The GTM engineer's job is answering “if you only had to work for one customer, what would you give them?” and operationalizing it: “It's not a clay problem. It is a so what problem.”
- **GTM engineer vs RevOps:** RevOps is CRM maintenance — “They are consumers of business strategy.” GTM engineers do “database origination”: connect strategy to outside data and orchestrate it into channels (LinkedIn, cold email, ads); best case they partner with RevOps and act as the translation layer between what reps do and what execs know.
- **Before hiring one, go prospect yourself:** imagine every SDR and AE is fired tomorrow and you must prospect for a day — do that, sit with sellers. “you can't ask someone to automate what you don't understand”; AI just makes you look more embarrassed if you don't know what to automate and why. Bolting AI onto the old account→persona→contacts→personalize→scale model is “putting a legless robot on a horse.”
- **Evaluate AI GTM tools by the copy:** “show me the copy” — if the copy shows no great data behind it, the LLM is inventing. Sold signals degrade as more people use them; the only one that really worked was champion movement “because your competitors can't copy it.”
- **Customer-backwards method:** best segment and why → 2–5 heuristics that imply tension → message (“The list is the message”) → AI only channelizes the message per channel → scale segment by segment, plus PVPs (“I'm trying to target myself out of a box”). Horizontal companies should verticalize motions or their “knowledge fractures not compounds.”
- **Systems of intelligence + the conductor CRO:** an LLM with your context in the middle, connected (via MCP) to systems of record (clean your CRM in the next six months — “No one has a clean CRM today”), systems of information (most underinvested: your own market database) and systems of action. The future CRO works with two to five people (a QA/editor with a critical eye, a customer storyteller, a database/RevOps person) and is “the conductor,” not the first-chair violinist. Start by having the team dump every call into a long-context model and ask “Tell me about my customers”; just start chatting with models — “the interface is not the limitation.”
- **Founder origin:** got fired from a lot of places — opinionated, no half measures; wants to suffer his own wrong calls “because the suffering is the education.”

## Building live on stage / one-person business (own channel, K43pi85WegU, 2026-10-06)

- Tech Week SF event (Oct 7, sponsored by Exa and FullEnrich): build GTM motions live from the stage with Claude Code on one side and slides on the other, and open-source the tools for everyone in the room — show the real work, not “the types of plays that you see on LinkedIn.”
- Runs a one-person business he says has grown 50–60% year-over-year every year; GTM engineer since 2020. Most expensive event means fewer people and higher-quality conversations; expects to break even and only took sponsors he uses — “I didn't want to turn this into a pitch show.”

