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


## Get Started Here — the GTM engineering method end to end (Substack 2026-10-08; Sculpt talk companion)

Free Substack post written up from his Oct 2026 Sculpt talk (Claude-drafted, “Approved by Jordan”). Message examples are templates with details changed, not case studies.

- **AI got spent on volume, not better messages:** reply rates fell from ~8.5% (Backlinko 2019) to ~3.43% (Instantly 2026) — directional, different datasets. “everyone got cheap intelligence and spent it on volume, and the messages didn't get better.” Bad examples need no LLM at all: “Following a company on LinkedIn isn't intent.”
- **Implementing empathy:** “The root cause is that we aren't grounded in our customers' daily lives.” “Models are spectacular at persistence” — point it at why buyers chose you, not first-line compliments; “use AI to internalize the voice of your customer.”
- **Four PVP templates:** drone photo of an OSHA violation to the facilities director; procurement overspend sized at the PE-firm level so silence means “I don't care about $1.3M”; permit data showing GAF roofers putting most roofs under other brands; scanning all of Gong's public case studies for champions who changed jobs (“what persistence makes possible”).
- **Part 1 — foundation:** one shared repo that remembers everything (start from Karpathy's LLM wiki), connect systems via CLIs (“usually beats an MCP connector” for bulk pulls), one account dossier per deal including the lost ones (“Your closed-won deals are the planes that came home”), push to GitHub so every fix compounds; public starter vs private repo for real customer data.
- **Part 2 — invert:** Munger's “how would I kill pilots” move; work backwards from real outcomes “instead of buying signals a vendor wants to sell you.” Segment by situation, not firmographic proxy (fleet size didn't matter; “I have a huge problem scheduling my trucks” did). Sort won / lost / 10X (lifetime revenue ≥10× median) and ask how you could have known beforehand. Qualify (yes/no bar) then quantify (more is better) — “Both come from your past accounts, not from a persona doc.”
- **System 1 scoring:** reasoning model builds an evidence packet per company; Jev (TypeSafe, $42 per billion input tokens) answers yes/no / probability / buckets across the whole market (79,601 people for $9.47 in one run). Calibrate the 0.90 cut-off on 30 hand-labeled rows before trusting it.
- **Part 3 — ship often:** Tyson's “plan until punched in the mouth”; “A slow test builds pressure to work; a fast one just teaches you.” If a campaign works (84% contacted → opportunities), juice it — “If you have a money printer, push the button more often.” Ask what your next best customer would steal (Skimmer: pool-cleaning price ranges by ZIP). Know the customer in your bones — “Hire someone who used to be your customer, or talk to customers until you know.”
- **Volume or value — pick one:** “You can use AI to send more of the messages nobody wants, or to send fewer that people would thank you for.” The one test: show the message to a prospect; if they say it would be really valuable, “every other question is downstream of that one.”
- **Free kit, paid depth:** the method, talk and six-skill GitHub starter (dossier auditor/builder, win-loss rewind, evidence packets + Jev judge) are free; $50/mo = paid articles + tool discounts; $2,499/yr = every tool he ships (Edge Copilot etc.).

## Sculpt compendium talk — spoken version of the method (own channel, unlisted, EwKQ9zC5cTg, 2026-10-06)

Solo first-person screen-share; captions approximate. Same method as the Get Started Here post; new here is how he says it and a few extra stories. Message examples are templates with details changed (he says he made some up).

- **Who he is on camera:** “I am a soloreneur. It's just me.” He does the work in clients' buildings; speaker and builder. The talk is a compendium for his Oct 7 and Oct 8 talks, with tools and discount codes in the paid post.
- **Why buyers don't respond:** no headline about 200 agents booking meetings unprompted, because “we've had a decade of eh” and a 2026 message “doesn't look much different than 2016.” Following a company on LinkedIn “is not any form of intent,” and nothing in a bribe-for-meeting pitch “requires a large language model.” Models are spectacular at persistence, and “if you are persistent about something that's useless, the result will also be useless.”
- **The only timeless strategy is empathy:** “the only timeless strategy that AI will never replace is to implement empathy” — use AI to internalize the voice of the customer, their daily life, buying environment, and why they chose you.
- **PVP = permissionless value prop:** “This is what I call a PVP, a permissionless value prop. The message is independently valuable to the person receiving it.” Ranks the drone-photo message above the cinnamon-cost one because the latter points to value without containing any, but the quantified ask still reads as “not replying to this message is essentially saying I don't care about $1.3 million a year.” Target the level where value is largest (the whole PE portfolio, not one company); the permit-data message is “a PLG motion” done “programmatically”.
- **Invert, don't buy signals:** Munger's weatherman story (“if I had to kill pilots, what would I do?”) → work backwards from customers; “Signals are things that vendors want to sell you.” Segment by shared situation (naming a scheduling problem beat truck-count targeting) and by relationship type, e.g. partners need a different message.
- **Know the customer in your bones:** a German ex-Coinbase founder spent three months doing a local dentist's paperwork before starting a dental-billing company; that intuition “AI can't replicate.” Skimmer made aggregate pool-cleaning price ranges by ZIP independently useful without exposing any one competitor. Ask what your next best customer would steal in one day.
- **Ship often; improve what works:** “Everything gets better when you ship often.” A slow test makes pressure grow when it should shrink. Don't chase new channels: citing a Brian Balfour post, “Most companies that got to 100 million did so with one channel.” With a campaign that converted 84% of contacts to opportunities he said juice it — “Nope, you have a money printer. Push the go button and push it often.”
- **The bar:** if a prospect sees your message and says it would be really valuable, “That's the bar. That's how you know,” then work backwards: right person, value only you can provide, a channel they're responsive to, validated with past customers or prospects.
- **Business model, as he states it:** $50/month tier for writing, $2,500/year tier with “a wiki that's updated all the time” and a “Jordan Crawford in Cloud Code” — his own description, not endorsed here.

## Cheap right answers / code before AI / pay for the filter (incremental 2026-10-14 — Substack Office Hours July 24th, pub 2026-10-13)

Free portion of https://edge.blueprintgtm.com/p/office-hours-july-24th-109-golfers (first-party Substack). Paid “below the line” builds not fetched.

- **Ask: right answer for close to nothing:** “how do I get the right answer for close to nothing?” Live Exa example: every golfer on LinkedIn in one country → 109 people for about a dollar.
- **Write code before you pay a model to think:** “The easy start is pointing a model at the problem. Most of the time that's a mistake.” Prefer scripts/keyword search (e.g. common first names for quotes on case-study pages; “doesn't pick up” / “doesn't answer” across hundreds of thousands of reviews) at $0 before paying for intelligence.
- **Optimize the outcome, not the agent:** “Some model providers are trying to optimize their agents. I care about optimizing the outcome, and ordinary software is very good at producing one.” His Crawford agent “tries the free path first.”
- **Start with Google; upgrade only when weak:** plain Google via a cheap tool first — “for most jobs… it simply returns better results than an AI search.” Switch to AI search when the task is harder or Google is weak.
- **Tool jobs:** Exa for people layer / finding and filtering people; Blitz when you need to go through everyone (e.g. every LinkedIn person in a country) and run your own filter.
- **Pay for the filter, not the dump:** “What you're paying for is the filter” — Exa’s edge is that “people pay over and over again to filter the same data.”
- **Universal signals don't pick buyers:** a signal every company sends (e.g. “AI enablement,” “who's spending too much on AI”) “can't pick a buyer.” Founders rarely post “I'm flaming out”; they post after they overcame it — so public stress signals mostly show up after the pain is gone.

## Unlimited intelligence / infinite-time problems / narrow and deep (own channel, -0doA9qurag, 2026-10-14)

Solo Waymo vlog on @BlueprintGTM; captions approximate (auto). First-party, spoken.

- **Don't chase every new tool; wait for a true leap:** “I basically don't move on things really quickly unless they provide a leap like a true leap forward.” Jev was the last one (“you could basically run intelligence on anything at like any scale”). He waits until the market votes with its behavior: “I'm an early adopter. I will take what the innovators do and let them figure out all the noise.” Credits Eric Nowoslawski as the crazy early adopter who told him about the next one.
- **Claude Code cloud projects are the latest leap:** a single orchestrator chat spins off sub-chats and sub-agents, with API keys in the environment, GitHub connected (“where all my context lives”) and his tools, kicked off from his phone. He runs routines after sales calls (“Yo, Claude, go do X, Y, or Z”). It lowers the bar versus stitching Railway/Vercel stacks together, “which I think is just genuinely good.”
- **Terminal no longer the default for customers:** “it used to be that I was pretty dogmatic about my customers using the terminal. I actually think it's like not the best surface for them anymore.”
- **Use AI for the annoying setup too:** when Eric said setup was a pain, he had Claude build a small local helper and Codex drive the computer to fill in the environment: “I know who can help. AI can help.”
- **Narrow and deep is how a one-person business compounds:** he solves the same problems over and over (data aggregation, data finding, data quality), so intelligence compounds. “this is the trick to running a very successful single person business is to just be narrow and go deeper and deeper and deeper.” Being “the AI platform for AIing” gets you nowhere. Says he expects to 2x his business this year while only posting on YouTube and Substack.
- **The question to ask: where does value accrue with more intelligence?** Personalizing an email more is diminishing returns: 5 hours versus 50 hours won't add value. Infinite-time problems compound. Example play for FullEnrich: find every B2B case study, every person named in them, check who changed jobs, then enrich them. “our main problem in go to market frankly is that we don't have enough ideas about these infinite time problems”; answer that and “most your go to market questions can be solved.”
- **Speaking (as of Oct 2026, time-bound):** GTM Shift events in Chicago, Austin and Miami in Oct–Nov 2026 (with Elaine Zelby, Jen Allen), plus the Vertical SaaS conference in Miami.

## Find, rank, build, check / run the tool for them (incremental 2026-10-16 — Substack “Live PVP Build For My Chicago Talk”, pub 2026-10-15)

Free Substack post (dc:creator Jordan Crawford; closes “— Written by Claude Opus 5.5, Approved by Jordan”). Lines marked as said on camera or typed into the session are his own words. Counts and costs are his stated results from one run.

- **Every campaign runs in four steps:** “Find the people,” “Rank them by fit and by how much they already engage with you,” “Give each one something useful built for them,” “Check every claim before it goes out.” The third step is the one most invitations skip.
- **Run the tool, don't describe it:** for his Chicago talk, Claude Code found 422 people he knows within 100 miles (LinkedIn connections + Substack subscribers; city matched against the US Census place gazetteer, which caught bugs like “KA, IN” being Karnataka, India), ranked them by Jev fit plus Substack stars, paid status and DM history (“counted per person, never read”), and built every emailable person a Google Doc of real tool output on their company. The first test report read well, then turned into a pitch for the annual tier: “The doc described what my tools would do for him. It never ran them.” His rule: every Doc “has to be useful to the person even if they never buy anything and never come.”
- **Where more AI time adds value:** more hours researching where you've spoken “is personalization, and it doesn't improve what I'd write to you”; more hours running a tool on your company and checking it does.
- **Check every claim, delete or hedge:** in the first test, 33 of 37 reports needed a fix (wrong founding years, an ended role shown as current, an internship inflated into “a decade”). Reviewers may remove or soften a claim but not write a new one, “because a new claim would need its own check.” Each Doc gets its own subagent, then a fresh skeptic subagent opens every link; Codex reviews via Dual Brain and blocked the plan twice before approving.
- **Pilot first, then spend:** Claude estimated $685–$1,035; real cost was about 19 cents a person in paid searches; four pilot Docs cost 77 cents and surfaced closed job postings and a passed deadline. Nothing goes out until he reads it.
- **The judgment only he can add:** speaker line (“They know me.”), cutting “Would be great to finally meet in person” because the email can't know whether they've met, one recommended tool per person, a separate version for annual members, one clear call to action. “My work is a narrow lane, and the models still can't run that lane without me.”
- **Closing advice:** before your next event, pull every contact within driving distance, rank by fit plus engagement, read one finished message before approving the rest.
- **Speaking dates (time-bound, as of 2026-10-15):** Chicago Wed Oct 21 (GTMshift, hands-on lab ~2:50–3:50pm Central), Miami Wed Nov 4 (Vertical Software Summit), Austin Thu Nov 12 (he corrects his own video, which said Nov 2).

## Other side of the transaction / pitch the felt pain / write your own first draft (incremental 2026-10-17 — Substack “Office Hours August 14th: Read the Sitemap Before the Website”, pub 2026-10-16)

Free portion of https://edge.blueprintgtm.com/p/office-hours-august-14th-read-the (first-party Substack, written up in his first person, byline Niqui). Paid “below the line” builds (sitemap method costs, school purchase records, insurance-adjuster build) not fetched. Customer names are from the session.

- **The evidence is usually already public:** “The evidence you need is usually already public, sitting in a file or a record the company published for some other reason.” To sort two million online stores, the cheap answer was the sitemap every store already publishes for Google (“Read the Sitemap Before the Website”).
- **Start on the other side of the transaction:** to find food distributors selling to schools, hospitals and hotels, don't search for distributors; schools publish what they buy, from whom and when, so you can map which distributors cover which districts and whose contracts are growing. “The seller rarely announces its customers. The buyer, especially a public one, often has to.” General rule: ask what trace the transaction leaves behind and who is forced to publish it.
- **Pitch the pain the buyer feels, not time saved:** reviewing a logistics campaign that pitched technician time savings: time savings are hard to sell (“Money saved from time saved is still a time-savings pitch”); the risk is bigger than the reward for an ops VP because “The stronger force now is fear of messing up”; and the person who cares may not hold the budget, so aim at whoever has to hear the daily complaint (“you'll never hear that complaint again”). Without sales-call transcripts showing why customers valued it, cold calling is how you find out: “People are very good at ignoring emails, and a phone call gets you feedback.”
- **Never let the model write the first draft:** “I never have a model write the first copy.” You end up editing longer than writing; he has “about 20 On the Edge posts I never published” because the prompt was too broad. Tell models ninth-grade level, no jargon, write like messaging a friend; a good cold message can sound like “Jordan, I've had to fire a bunch of people recently. It's the worst. Have you ever had to do that?”
- **Software engineering is like electricity:** some goods stop being useful past enough (food); electricity finds new uses every time it gets cheaper, and “Software engineering is now like electricity,” so advantage moves from managing people to building. People need two jumps: from Claude's co-work mode into Claude Code, then to seeing why a skill on an improving corpus (his Edge Copilot) sits on top.
- **Scope around speed, not hours:** asked whether a quote meant him full time for six months: “No. I design my scope around what I'm extremely fast at”. “My job is to shift the fulcrum, not to add more lever.”

## Stay on the working channel / send the data the buyer can't see / teach the model by example (incremental 2026-10-20 — Substack “Office Hours August 21st: Send Them the Out-of-Stock Sheet”, pub 2026-10-19)

Free portion of https://edge.blueprintgtm.com/p/office-hours-august-21st-send-them (first-party Substack in his first person, byline Niqui). Paid builds below the line not fetched. Attendee names are from the session.

- **When one channel works, stay on it:** told a founder whose cold calls were closing not to send the warm-up email campaign. “People avoid uncomfortable things and spend lots of time and effort on comfortable things that are less effective.” Do the math on what works (50 calls per meeting, $20,000 deal, so each call is worth about $50). “Most teams over-experiment instead of doubling down on the thing that's clearly working.” Email doesn't warm anyone up: “People are busy.” Fix the real constraint (time zones) with a local caller you train. “It's easier to make something that already works work better than to go from zero to one on a new channel.”
- **Send the data the buyer can't see:** the best message is built on asymmetry, e.g. telling a brand how often its product was out of stock at each store. “That message works because there's asymmetry between what he knows and what the buyer wants to know.” Before scaling, show it to an existing customer and ask if they'd respond; if they already get that list weekly, change the offer.
- **Teach the model how you decide, by example:** “It's a lot easier for Claude to reason backwards from worked examples than to reason forwards from instructions.” Record a person qualifying 50 websites and narrating their reasoning; do the first ones by hand. “Human reasoning is easy for an agent to copy, and headless automation gets none of it.”
- **Split every job into human parts and AI parts:** most people bolt AI onto the job they already have; take the job apart instead. That's why “AI SDR” struggles: it lumps human and automated moments together. “A new hammer doesn't mean you rebuild the house from scratch.” Hire people who want to play with the tools; founders and former founders are a shortcut.

## Ask for the outcome, not the tools: four kinds of ambition (incremental 2026-10-20 — Substack “Speaker Finder: The Best Speaker for Your Event, in Any City”, pub 2026-10-18)

https://edge.blueprintgtm.com/p/speaker-finder-the-best-speaker-for (first-party Substack; the post itself says it was written by Claude and approved by him, so prefer the lines he speaks in the video, quoted in the post).

- **Altitude over tools:** his first prompt named tools; the rewrite asked for a great speaker and let Claude propose the method. “The altitude is go find a good speaker.” He uses Felix Rieseberg's four kinds of ambition with a model (speed, altitude, depth, range).
- **Depth: ask how the field's best person would do it:** for speakers that's an event organizer (proof on stage, a name that sells tickets, a topic the lineup isn't covering).
- **Cheap checks on the most people, expensive reading on the fewest:** sweep about 20,000 people, screen with a cheap scoring model, check live profiles, read recent posts, then vet 40 finalists with sourced packets. “I think it would be too expensive to use reasoning models here.” Cut people still talking about old-era playbooks.
- **The warm network often wins:** the search surfaced someone he already knew: “all of this AI work just surfaced someone that I already knew, and I just texted him, and now he's in.” He admits the AI work was “a little bit useless” for his own panel, but useful for people running events.
- **Rewrite any tool-naming prompt with four lines:** outcome (what a great result looks like), expert (who does this best and how), range (other fields that could help), plan (ask for a plan and questions before spending anything). “I'm not adopting new tools every day.”
- **Speaking dates (time-bound, as of 2026-10-18):** keynote at GTMshift's The AI-Fluent Revenue Leader, Austin, Thu Nov 12, 2–6 PM.

## Read how companies sell, not what they are: the job-posting census (incremental 2026-10-23 — Substack “Here's a list of every U.S. sales team with 36 data points. 25 aren't in ZoomInfo.”, pub 2026-10-22)

Free portion of https://edge.blueprintgtm.com/p/heres-a-list-of-every-us-sales-team (first-party Substack, first person). Paid sheet below the line not fetched.

- **Filters describe what a company is; the question is how it sells:** a rep filtering “United States, software, 200 to 2,000 employees” gets twenty thousand companies and no answer. “The problem is that every available filter describes what a company is, and the question is about how it sells.” Companies write that answer down themselves in job postings; he read 2,317,725 of them across 21,783 US companies.
- **Most sales teams have no specialists:** 18,448 of 21,783 (84.7%) have no SDR title anywhere; about one SDR per 102 reps and one enablement person per 106. So an SDR tool really has about 3,300 companies that already decided the job should exist. “At those 3,300 you are not asking anyone to invent a budget. The job already exists, so the money already exists.”
- **One CRM, then a cliff:** Salesforce named in 32.0% of companies' hiring, HubSpot 12.6%, ZoomInfo 6.4%, Gong 5.7%, Salesloft 4.2%, enablement platforms about one in fifty. A company naming Gong and Salesloft already has budget, buyer and a habit of evaluating tools. Only 8.3% name a selling method, so “At nineteen companies in twenty, there is nothing to rip out first.”
- **Data vendors answer the wrong question, and that's not their fault:** 25 of his 36 columns have no ZoomInfo filter (checked against ZoomInfo's own technical docs, giving them every close call). “This is not a failure on ZoomInfo's part.” Facts about how a company sells “live in text the company publishes about itself, which means somebody has to read it.”
- **Sales complexity is an industry fact, not a size fact:** scored 0–100, security and IT services near 71, biotech 67, software 62, retail 19, real estate 5 (agent networks look like sales teams but can't buy). “So the vertical worth sorting on is not "fintech". It is "four people in the room and one of them is technical".”
- **Read everyone, then sort:** reading 22,681 companies cost $3.92 in overnight batch (about $75 on a mid-tier model). “You read everyone, then sort.”

## Pipeline Council session: why buyers don't respond (incremental 2026-10-25 — Scale Venture Partners Pipeline Council, video 2026-10-08, write-up by Craig Rosenberg 2026-10-20)

Sources: https://www.youtube.com/watch?v=RN4DSQE4EHU (his talk, auto-captions, wording approximate) and https://www.howwescaledthis.com/p/give-away-the-info-your-buyer-would (host write-up; only lines it attributes to him are used). Overlaps his Sculpt compendium talk; new points below.

- **Reply rates fall because agents now run the old SDR playbook:** pound the phones, send emails, talk about yourself. The root cause is not being grounded in the customer's daily problems, which is worst for horizontal SaaS (his examples: a prospecting message from an AI startup that didn't filter out its own employee, and AirPods-for-meetings bribes, which he concedes “work”). Judge any AI SDR or revenue tool by one thing: “look at the message it produces.” Once you have a system that understands customers' problems, “no AI from your competitors is going to out message you”.
- **Shared GTM repo for dossiers:** one file per deal, won and lost, trusting customer actions, then customer words, then the CRM last; push it to GitHub like product code so corrections compound: chats and private Claude Code sessions give “no chance for compounding intelligence”.
- **Qualify, then quantify:** after sorting a segment into won, lost and 10x customers, ask how you could have known the bucket before they came inbound; qualification is whether to sell at all (e.g. too big, already on an ERP, no risk person), quantification is what makes a 5x/10x/100x customer (e.g. a high ratio of risk adjusters to headcount).
- **Execute the information edge:** a plastics-ERP founder who knew the price of resin (80% of customer spend) five days early should just send customers that number; he jokes the founder should quit software and bet the venture money on prediction markets instead. The founder didn't do it, which is why “it's always best to improve what's working.”
- **Hire someone who sat in the customer's seat, or run a customer council:** his own Michelin-dinner event idea was overruled by someone who knew the buyers wanted beers and wings, and that event was “so successful”.
- **Leaders build the list and the message; reps run it (per write-up):** asking a new grad to figure out who to target and what to say in three months is “a ridiculous thing to ask.” Treat reps as customers of the list and fix it from their feedback.
- **Pay the first rep for learning speed (per write-up):** citing Munger on incentives, pay a flat rate before the motion is repeatable and reward how fast the rep can say whether an experiment worked and why, aiming for one clear result a week. Every outbound message is “selling a conversation.”

## Where more AI hops add value (incremental 2026-10-27 — @BlueprintGTM video 2026-10-26)

Source: https://www.youtube.com/watch?v=MK9lnq0fn8c (his own channel, solo, auto-captions; wording approximate). Model and tool names are his examples.

- **Pick AI tasks by whether the next hop adds value:** ask “where does the next hop add incremental value?” His example is a tool that scans a whole TAM for missing money: more intelligence can confirm the money is theirs, fill in the claim, and submit it, so every hop adds value. Narrow personalization (“I saw...”) is the opposite: more intelligence adds nothing. Aim for the tasks where more intelligence turns outreach into “a self-driving car.”
- **Don't let AI talk to serious buyers:** when he asked two frontier models for the best use of AI in GTM, one said qualifying and disqualifying buyers, which he calls the opposite of what you want: “You do not want an AI having a conversation with an interested buyer that's going to spend 20K plus”, for human reasons; maybe for small SMB deals. The other said training people, which “can't be the best use” because only two or three in a hundred-person org will adopt it, while models can run forever.
- **The message, not deliverability:** outbound groups obsess over getting into the inbox but send the same message that sits in spam, forgetting they are trying to change someone's behavior.
- **The data is the hard part:** at his Chicago talk he tried to build a GTM strategy and a lead list for everyone in the room; he scrapped the messages because they didn't sound like him, but “the hardest part is discovering the data and what's useful.” He doesn't repeat talks (next: Miami, then Austin).
- **Permissionless value prop:** “Write a message so good that people would pay to receive it.” Ask what public information would be really valuable to this person that they can't get from a basic Google search or chatbot request; “You can make the world come to your prospects.”
