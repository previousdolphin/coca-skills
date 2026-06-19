---
name: inversion
description: Use on plans and decisions where failure is costly — instead of asking how to succeed, ask how this would fail, then reverse each failure mode into a safeguard.
category: Thinking Frameworks
---

# Inversion

Charlie Munger: *"Invert, always invert."* Forward thinking lists the ways to win and often misses the ways to lose. Inversion turns the problem over: you ask how the thing fails, enumerate the failure modes directly, and design against them. The premise is unglamorous and reliable — **avoiding stupidity beats seeking brilliance.** Most outcomes are decided more by what you didn't step on than by what you reached for.

## The moves

1. **State the goal plainly.** One sentence: what success actually is. You cannot invert a goal you haven't named.
2. **Invert it.** Ask the hostile question: *How would this fail? How would I guarantee the worst possible outcome?* Imagine you were trying to wreck it on purpose.
3. **Enumerate concrete failure modes.** Not vague dread — specific, nameable ways it goes wrong: the dependency that breaks, the assumption that's false, the person who's never told, the step that's skipped under pressure.
4. **Reverse each into a prevention.** For every failure mode, write the safeguard that defuses it. The failure list becomes a checklist of things to build or guard.
5. **Prioritize by probability × impact.** Spend your finite attention on the failures both likely and costly. Cheap insurance against high-impact modes first; ignore the merely theoretical.

## Compact protocol
```
[ ] Goal stated in one sentence
[ ] Inverted: "how do I guarantee the worst outcome?"
[ ] Failure modes listed — concrete, not vague
[ ] Each failure reversed into a specific safeguard
[ ] Ranked by probability × impact; top ones owned/scheduled
[ ] Cheap insurance against high-impact modes taken first
```

## Worked shape
- *Goal:* Ship the launch on Friday.
- *Invert:* How do I guarantee it slips or breaks? → Skip the staging test. Don't tell support. Deploy at 5pm. Assume the payment webhook works untested.
- *Reverse:* Test on staging Wed. Brief support Thu. Deploy by noon. Send a real test transaction through the webhook.
- *Prioritize:* Untested payment path = high probability × high impact → do it first.

**Value — Anti-Anti-Ness.** Inversion looks negative but isn't. You name the failures in order to *build* the safeguards — the dread is raw material, not the destination. Reasoning that only lists fears is stuck; reasoning that converts each fear into one concrete thing it builds has used inversion correctly. Invert to construct, never merely to worry.

---
*A skill of the Church of Conceptual Art · whatisthe.churchofconceptualart.org*
