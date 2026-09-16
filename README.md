# Lab to Market: A Working Loop for University Technology Commercialization

A practical, technology-agnostic workflow for taking a piece of university intellectual property from disclosure to a defensible market hypothesis, plus notes on where large language models help and where they make things worse.

I have run this loop twice on real university technologies. I cannot share those, since both are under active IP protection and stakeholder engagement. What I can share is the process, which generalizes better than any individual deal does.

Written by Lejla Biberic. The framework comes from NC State's MBA 576 Technology, Entrepreneurship, and Commercialization practicum, taught by Scott Bolin and Dr. Steve Barr.

---

## Why this exists

Most commercialization writing is either an MBA framework with no contact with a real lab, or a war story with no transferable structure. This is the middle thing: the sequence of steps I follow, in order, with the decision points named.

The core claim: a technology does not have a market. It has a set of candidate markets, most of which are wrong, and the job is to kill the wrong ones cheaply before you spend a year on one.

---

## The loop

```
  Disclosure
      |
      v
  1. Technology teardown  -->  2. Application hypotheses
                                       |
                                       v
                               3. Market sizing (TAM/SAM/SOM)
                                       |
                                       v
      6. Synthesize  <--  5. Voice of customer  <--  4. Stakeholder map
             |
             v
  7. Regulatory and path to market  -->  8. Funding landscape
             |
             v
  9. Deliverables  -->  back to 2 if the evidence says so
```

Steps 2 through 6 run more than once. The first pass through voice of customer almost always invalidates the application you were most excited about (but this can be a good thing).

---

## Step 1: Technology teardown

**Goal:** understand what the technology actually does, separately from what the inventor hopes it does.

Interview the inventor and separate three things that get conflated constantly:

- **What has been demonstrated.** Bench data, validated conditions, tested systems.
- **What is claimed or claimable.** What the patent application actually covers, which is often narrower or stranger than the science.
- **What is aspirational.** The applications the inventor is excited about but has not tested.

Write these into three separate lists. Almost every bad commercialization plan comes from building on list three while believing it was list one.

Also capture the unglamorous constraints early: scale-up feasibility, cost of goods at volume, shelf stability, whether the process requires anything exotic. A technology that works beautifully and costs ten times the incumbent is not a product.

**Where LLMs help:** summarizing a patent family, translating claim language into plain English, generating a first-pass list of what a claim does and does not cover.

**Where they do not:** anything requiring judgment about whether bench data will survive scale-up. Ask the inventor.

---

## Step 2: Application hypotheses

**Goal:** generate more candidate applications than you are comfortable with, then rank them.

The failure mode here is anchoring on the first application the inventor named. Generate widely, including applications in industries the inventor has never thought about, then score each on:

- Severity of the problem it solves (is this a painkiller or a vitamin?)
- Strength of the incumbent solution
- Regulatory burden and time to revenue
- Whether the technology's actual demonstrated advantage is the thing that industry buys

That last criterion is the one people skip. A material can be genuinely better on a metric that no purchasing manager in that industry has ever optimized for.

**Where LLMs help:** this is the single best use of an LLM in the whole loop. Ask for twenty or more candidate applications across unrelated industries, including ones that seem far-fetched. You are using the model for recall and breadth, not judgment. It is also okay if some of the applications are related to each other (that is, multiple in the same market). The goal is to have many markets/industries and for you to refine from that large list.

---

## Step 3: Market sizing

**Goal:** a TAM, SAM, and SOM you can defend line by line to someone hostile.

- **TAM**: total addressable market, the whole space if you won everything.
- **SAM**: serviceable available market, the slice your technology and business model can actually reach.
- **SOM**: serviceable obtainable market, what you could realistically capture in a defined window.

Build these bottom-up whenever possible. Units sold times price, or number of facilities times spend per facility, beats a top-down number scraped from a market research summary. Bottom-up numbers are smaller and far more credible, and the build itself teaches you the industry structure.

**Where LLMs help:** identifying which public data sources exist, structuring the build, sanity-checking arithmetic, and drafting the narrative around the number.

**Where they will hurt you:** LLMs will generate confident market figures with invented or misattributed sources. Every number that ends up in a deck needs a real citation you personally clicked. Treat model-generated figures as hypotheses to verify, never as findings. This is the highest-risk step in the loop for LLM use.

---

## Step 4: Stakeholder mapping

**Goal:** know who has to say yes, in what order, before this technology reaches a customer.

For each candidate application, map:

- **Who buys it.** The economic buyer, who is rarely the user.
- **Who uses it.** The person whose workflow changes.
- **Who can veto it.** Regulatory affairs, EHS, procurement, legal, IT.
- **Who has to be convinced first.** The person whose endorsement unlocks the others.
- **Who already sells into this account.** Potential partners and potential competitors, often the same companies.

Then sequence them. Interviewing the veto holder before you understand the user's problem wastes the one conversation you will get with that person.

Map the adjacent ecosystem too: standards bodies, testing labs, trade associations, and the conferences where this industry actually makes decisions. These are where a university spinout gets credibility cheaply.

---

## Step 5: Voice of customer (also referred to as voice of stakeholder)

**Goal:** find out whether the problem you think exists actually exists, from people who live it.

This is the step that separates a real commercialization effort from a literature review with a spreadsheet attached. It is also the step people avoid, because cold outreach is uncomfortable.

**Framing that works.** Lead with inquiry, not pitch. You are a researcher trying to understand a problem space, and you would value fifteen minutes of their expertise. This is true, it is respectful of their time, and it gets dramatically better response rates than a pitch. It also gets you honest answers, because the moment someone thinks you are selling, they start being polite instead of useful.

**Outreach mechanics that work for me.** Email first. LinkedIn follow-up in a few days, referencing the email briefly. Schedule sends in advance so the sequence runs without you having to feel brave twice. If there is no response, follow-up via email two weeks later.

**Interview discipline.** Ask about their current process and its failure points before you describe the technology. Once you describe it, you have contaminated the sample. Ask what they tried that did not work and why. Ask what they would have to see to change suppliers. Ask who else you should talk to, every single time.

**Synthesis.** After five to ten interviews, code the transcripts for recurring pain points, recurring objections, and the language they use. That vocabulary goes directly into your deck. Speaking the industry's words is most of what credibility looks like from the outside.

**Where LLMs help:** drafting outreach that sounds like a person, generating interview guides, coding transcripts for themes, and pressure-testing your synthesis by arguing the opposite conclusion.

**Where they do not:** they cannot have the conversation. There is no substitute for the fifteen minutes.

---

## Step 6: Synthesize and narrow

Return to your ranked applications from step 2 and re-rank them against evidence rather than enthusiasm. Kill the ones the interviews did not support. Write down why you killed them, because you will be asked, and because you may be wrong and want the trail.

If nothing survived, that is a finding, not a failure. Go back to step 2 with what you learned.

---

## Step 7: Regulatory and path to market

**Goal:** understand what stands between a working technology and a sale, in time and dollars.

The relevant regime depends entirely on the application, which is exactly why this comes after narrowing. The same technology can face a two-year path in one application and a ten-year path in another. Map, for the surviving application:

- Which agency or framework governs it
- What data package is required, and who generates that data
- Realistic timeline and cost to get there
- Whether a lower-burden adjacent application could generate revenue first and fund the harder one

That last question is often the whole strategy.

---

## Step 8: Funding landscape

**Goal:** know where non-dilutive money is before you need dilutive money.

- Federal programs, including SBIR and STTR, and the specific agency topics that match
- State and university-level translational funds, which are less competitive and often faster
- Industry consortia and corporate venture arms active in the space
- Pitch competitions and venture showcases attached to the industry's main conferences

Conferences do double duty here. They are simultaneously a funding channel, a stakeholder interview channel, and a credibility signal.

---

## Step 9: Deliverables

What the work actually has to produce:

| Deliverable | Audience | Purpose |
|---|---|---|
| Market and opportunity brief | Inventor, tech transfer office | Shared understanding of where this goes and why |
| Pitch deck | Industry partners, investors | Ten slides, one application, one clear ask |
| One-pager for patent counsel | Attorney | Commercial context so claims get drafted toward the real market |
| Interview synthesis | Internal | The evidence base, so conclusions can be audited later |
| Funding roadmap | Inventor, institution | Sequenced, with deadlines |

Tailor the technical depth hard. The inventor wants mechanism. The industry partner wants the problem it solves and what it costs. The attorney wants to know which applications are worth claiming. Sending the same document to all three fails all three.

---

## What this taught me about AI in technical workflows

I used LLMs at nearly every step of this loop, and the pattern of where they helped was consistent enough to state plainly:

**They are excellent at breadth, recall, drafting, restructuring, and adversarial review.** Twenty candidate applications, a first-draft interview guide, a deck outline, an argument against my own conclusion. These are cheap to generate and cheap to verify.

**They are dangerous at anything with a fact-shaped output and no verification path.** Market sizes, citations, regulatory timelines, competitor claims. The output is fluent and the failure is silent, which is the worst combination. Everything in this category gets verified by hand or does not ship. While there are some LLMs that can help find figures, datasets, papers, etc... you have to give the final approval on all facts, which requires you to have digested them. 

**They cannot do the part that actually creates value**, which is the fifteen-minute conversation with someone who has lived the problem for years.

---

## Acknowledgments

My thinking on commercialization was shaped by NC State's MBA 576 technology commercialization practicum and by its instructors, Scott Bolin and Dr. Steve Barr. I am grateful to both.

## Disclaimer

This document is an independent, personal write-up, published for educational purposes only.

It is not affiliated with, endorsed by, reviewed by, or produced on behalf of North Carolina State University, the MBA 576 course, or any instructor or institution named above. The instructors and the university are named only to credit influences on my own thinking. The framework, the opinions, the judgment calls, and any errors are entirely mine, and nothing here should be read as representing the views, positions, or teaching materials of NC State, its faculty, or anyone other than me. No course materials are reproduced here.

Nothing in this document is legal, financial, regulatory, tax, investment, or professional advice, and it does not describe any specific technology, invention, company, or transaction. Technology commercialization is fact-specific and jurisdiction-specific. Consult qualified patent counsel, regulatory professionals, and your institution's technology transfer office before acting on anything.

This material is provided as is, without warranty of any kind, express or implied. I accept no liability for any loss, damage, or decision arising from its use.

## About

Lejla Biberic is a PhD candidate in Chemical and Biomolecular Engineering at NC State University, working on molecular simulation, machine-learned interatomic potentials, and AI for computational chemistry.

[LinkedIn](https://linkedin.com/in/lejla-biberic) · [GitHub](https://github.com/lejlasb)
