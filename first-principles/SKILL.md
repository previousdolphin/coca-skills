---
name: first-principles
description: Use on novel or complex problems, or when an "obvious" assumption is steering you — break the thing down to bedrock facts and rebuild, instead of reasoning from analogy.
category: Thinking Frameworks
---

# First Principles

Most reasoning is by analogy: *it's like the last thing, so do what worked there.* Analogy is fast and usually fine — until the new problem isn't like the old one, and the inherited assumptions quietly carry the failure with them. First-principles reasoning strips a problem to facts that cannot be reduced further, then rebuilds upward from those alone. Slower, but it sees what analogy hides.

## The moves

1. **State the belief plainly, and why you hold it.** Write the claim and the reason in one sentence each. If you cannot state the reason, that is the first finding.
2. **Challenge each assumption.** For every load-bearing premise ask: *Is this truly true, or merely received?* Then consider the opposite — *what if it weren't so?* An assumption that survives its own inversion is closer to fact.
3. **Five Whys to bedrock.** Ask "why" of each premise, then of the answer, five times or until you hit something irreducible — a physical limit, a definition, a verifiable fact. That floor is a first principle. Everything above it was inference.
4. **Rebuild upward.** From the bedrock facts only, reconstruct a solution. Allow it to differ from the inherited one. Often the rebuild reveals a constraint that was never real.
5. **Name your mode out loud.** For each conclusion, mark it: *from first principles* (derived from bedrock) or *by analogy* ("it's like X"). Analogy isn't wrong — but you should know which you are doing, and never mistake one for the other.

## Compact protocol
```
[ ] Claim + reason written, one sentence each
[ ] Each assumption tested: truly true? what if the opposite?
[ ] Five Whys run to an irreducible fact
[ ] Bedrock facts listed explicitly
[ ] Solution rebuilt from bedrock, allowed to differ
[ ] Every conclusion tagged: first-principles vs analogy
```

## Worked shape
- *Belief:* "We need a 6-month timeline." *Why?* "That's how long it took last time."
- *Challenge:* Is the timeline a fact or a memory? What was actually slow?
- *Five Whys:* Why 6 months → because integration took 4 → because the API was undocumented → because no one asked for docs → because we assumed analogy to the prior vendor. **Bedrock:** the integration time, not the calendar, is the real constraint.
- *Rebuild:* Solve the documentation gap directly; the 6 months was inherited, not required.

**Value — congruence.** The discipline here is refusing to let an assumption wear the costume of a fact. Tag what you actually know versus what you've merely been carrying; speak the two differently. A plan built on honest bedrock holds; one built on disguised assumptions fails exactly where you weren't looking.

---
*A skill of the Church of Conceptual Art · whatisthe.churchofconceptualart.org*
