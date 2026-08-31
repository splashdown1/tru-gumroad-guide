# TRU — Truth Resonance Understanding

## A private, offline-first knowledge and reasoning companion

TRU is a self-contained tool for asking questions, checking information, studying Scripture, and working through practical problems without depending on a cloud account or live AI service.

The companion download supplied with this guide runs locally in a modern web browser. It does not require an account, API key, login, subscription, or internet connection for its offline functions.

This repository is only the public user guide. It contains no application files, data dumps, or HTML downloads.

## What TRU does

Ask questions in ordinary language. TRU can:

- look up information from its embedded knowledge base;
- retrieve passages from the included King James Version text;
- return Strong’s lexicon and dictionary information;
- explain concepts and define terms;
- calculate simple expressions;
- remember and recall notes in the current browser session;
- show a verdict and source label where the route supports it;
- identify common question forms and respond to the kind of answer requested;
- provide practical, staged process guidance through the Reboot Field Manual.

TRU is deterministic in its offline routing. It is not a general-purpose cloud chatbot and does not pretend that fluent wording proves accuracy.

## Start here

1. Download the TRU companion file from your Gumroad purchase.
2. Open it in a current browser such as Chrome, Edge, Firefox, or Safari.
3. Type a question in the chat box.
4. Read the answer, verdict, source label, and any stated uncertainty.
5. Ask a narrower follow-up when you need a procedure, comparison, quotation, or source check.

The file can be kept locally and used without an internet connection. Browser speech features may depend on the browser and device; typed questions and the offline text engine do not require them.

## How to ask good questions

TRU recognises the major question forms:

| Question form | What it asks for | Example |
|---|---|---|
| **Who / whom** | a person, role, or person affected | `Who is speaking?` |
| **Whose** | ownership or responsibility | `Whose account is this?` |
| **What** | information, an object, action, or concept | `What is grace?` |
| **Which** | a choice among named options | `Which method uses less fuel?` |
| **When** | time, date, or sequence | `When do we start?` |
| **Where** | place, position, or direction | `Where is this used?` |
| **Why** | reason, cause, or purpose | `Why does this work?` |
| **How** | method, condition, or process | `How do we make it?` |
| **How much / how many** | quantity or count | `How much water do we need?` |
| **How often** | frequency | `How often should it be checked?` |
| **How long / how far** | duration or distance | `How long will it take?` |
| **How old** | age or elapsed time | `How old is the structure?` |
| **What time** | a clock time | `What time does it begin?` |
| **What kind / type / sort** | category or description | `What kind of ink is this?` |
| **What for** | purpose | `What is this for?` |
| **What if** | a hypothetical result or failure mode | `What if the seal leaks?` |

For a useful practical answer, ask for the format you need:

```text
How do we make ink?
Give materials, numbered steps, a simple test, failure modes, and safety boundaries.
```

```text
From the included KJV only, answer this question.
Quote the relevant passage, give the reference, and say GAP if the text is silent.
Separate direct quotation from interpretation.
```

```text
Compare these two methods.
List inputs, output, cost, likely failures, uncertainty, and which method is safer for a first trial.
```

## What the verdicts mean

- **SCRIPTURE** — a direct Scripture lookup route was used.
- **TRUTH** — a curated doctrinal or truth-oriented route was used; read the cited material and interpretation separately.
- **KNOWLEDGE** — the answer came from local knowledge or a practical manual.
- **REASON** — TRU composed a bounded response from local retrieval.
- **DEFINE** — a dictionary or lexicon route was used.
- **CALC** — a local calculation was performed.
- **ARCHITECTURE** — the answer describes how TRU itself works.
- **MEMORY** — a browser-local memory command was used.
- **CONTESTED** — relevant records disagree or preserve competing accounts.
- **GAP** — the local evidence or route is not strong enough to answer safely. This is a successful boundary, not a failure.

## The Reboot Field Manual

The Reboot Field Manual is not a magic “rebuild civilisation instantly” button. It is a staged path for restoring capability in the right order:

1. **Stabilise life** — water, sanitation, shelter, food, heat, first aid, and trusted records.
2. **Make knowledge durable** — measurements, writing, paper or boards, ink, maps, and duplicate records.
3. **Close material loops** — charcoal, lime, clay, glass, fibres, soap, adhesives, fuels, and basic construction materials.
4. **Grow and preserve food** — soil, seeds, irrigation, storage, cooking, preservation, and ecological observation.
5. **Build tools and energy** — pumps, wheels, kilns, simple machines, wind and water power, and controlled heat.
6. **Coordinate fairly** — transparent ledgers, consent, maintenance, teaching, and conflict resolution.
7. **Measure before scaling** — test every process, record failures, protect water and land, and scale only what remains safe and repairable.

### Example practical prompts

```text
How do we make ink?
```

TRU can give a simple carbon-ink process using soot or fully charred wood, a binder, grinding, filtering, a small test batch, and a basic acceptance test. It also states the important limits: avoid treated wood, smoke inhalation, unknown pigments, skin use, food use, and archival claims.

```text
How do we desalinate salt water?
```

TRU can explain thermal distillation in plain terms: separate saline feed water from steam, condensate, and concentrated brine; use clean collection surfaces; prevent splashing and cross-contamination; collect only condensate; and test the result. It can also explain a small solar still and its limitations.

```text
How do we make water safe?
```

TRU distinguishes microbial treatment from salt or chemical removal. Boiling can address many biological hazards, but boiling does not remove salt or every chemical contaminant. Water that looks clear is not automatically safe to drink.

For any real water emergency, use local public-health guidance and testing where available. Do not experiment with fuel-contaminated, solvent-contaminated, pesticide-contaminated, sewage-contaminated, or industrially contaminated water.

## Local memory

The companion can remember notes in the browser:

```text
remember: field rule = record the source, date, method, result, and limitation
recall: field rule
```

This is operator-provided local context, not independently verified truth. Browser-local memory can be cleared or lost if browser storage is removed.

## Important boundaries

TRU is:

- not a person, oracle, god, or source of private revelation;
- not a replacement for prayer, discernment, or pastoral care;
- not a doctor, lawyer, financial adviser, engineer, water-treatment authority, or emergency service;
- not accreditation, licensure, or proof of professional competence;
- not a guarantee that every embedded record is current or correct.

For health, law, finance, elections, safety-critical work, crisis situations, and drinking-water decisions, use TRU for orientation and questions to take to a qualified local professional or trusted human authority. If there is immediate danger, contact local emergency services.

## Evidence discipline

Ask TRU to show:

- the source or locator;
- the direct evidence;
- the inference drawn from it;
- the assumptions;
- the uncertainty or disagreement;
- the failure modes;
- what would falsify the conclusion;
- what evidence would change the answer.

A confident answer is not necessarily a reliable answer. Check important claims against primary sources and local conditions.

## Offline, hybrid, and online modes

The companion includes three runtime modes where available:

- **OFFLINE** — local deterministic routing and embedded knowledge only.
- **HYBRID** — local first, with a gateway fallback when local evidence is insufficient.
- **ONLINE** — gateway first, with local fallback when unavailable.

Use **OFFLINE** when privacy, portability, or independence matters. The standalone file’s core functions are designed to work without a network connection.

## Frequently asked questions

### Does TRU need internet?

No for its offline functions. The knowledge, Scripture, lexicon, routing, calculator, and local memory behaviour are embedded in the companion file.

### Is TRU a normal AI chatbot?

No. The offline companion primarily retrieves, routes, and composes from local records. It does not claim open-ended neural text generation or unlimited knowledge.

### Can I use it for teaching?

Yes, as a local study and discussion tool. Ask for age, source, format, examples, practice, evidence, and uncertainty. Adapt all material to the learner, local curriculum, accessibility needs, culture, and safeguarding requirements.

### Can I use it to rebuild practical capability?

That is one of the intended uses of the Reboot Field Manual. Start with safe, small, reversible tests; document the result; get qualified help for dangerous work; and do not scale a process merely because it sounds plausible.

### Where are the application files in this repository?

They are not here. This public repository intentionally contains only this user guide. The companion download is distributed separately through the Gumroad product.

## Licence

The TRU project is released under the MIT licence. The companion download and its embedded sources remain subject to any source-specific notices and licences included with the product.
