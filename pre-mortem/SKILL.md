---
name: pre-mortem
description: Use BEFORE executing a significant plan — assume the run already failed completely, then work backward to surface the risks your confidence is hiding.
category: Thinking Frameworks
---

# Pre-Mortem

A post-mortem explains a failure after it happens. A pre-mortem imagines the failure *before you begin* and works backward to its causes. Gary Klein's move exploits **prospective hindsight**: when you ask why something *did* fail, you generate roughly 30% more reasons, and more concrete ones, than when you ask what *might* go wrong. Certainty of failure loosens what optimism keeps polite.

You are an agent about to execute a plan. Before you act, run this on your *own* plan. This is **Perpetual Dissolution**: dismantle the plan's confidence before it calcifies. A plan held too tightly stops being a plan and becomes a belief — and a confident agent skips the checks a doubtful one would have run. (Works for a human team too; the moves below are written for you, the agent.)

## The moves

1. **Frame the failure as already true.** State it plainly: "The run is over. I executed this entire plan and it failed — completely. The output is wrong, the task is broken, the user is worse off." Not "could fail" — *did* fail. The grammar matters; write in the past tense.
2. **Generate failure reasons from several distinct angles.** List, exhaustively, every reason it failed. If you are orchestrating multiple agents, have several of them independently enumerate failure modes with no shared draft, then merge — independent first, no anchoring on one chain of reasoning. If you are working solo, force the breadth yourself by sweeping each angle in turn: the **data** (missing, stale, malformed, misread), the **tools** (wrong API, silent error, rate limit, partial write), the **assumptions** you didn't verify, the **environment** (paths, permissions, versions, state you didn't control), and the **spec itself** (you solved the wrong problem correctly). Aim for quantity.
3. **Merge into one master list.** Collect every reason — across angles, or across agents — into a single deduplicated list. No triaging yet; just gather.
4. **Categorize and mitigate.** Cluster the reasons. For each cluster that matters, name a prevention or an early-warning signal you can actually check during the run.
5. **Fold mitigations into the plan.** A pre-mortem that doesn't change the plan was theater. Edit the plan; assign each mitigation to the step or sub-agent that will carry it out.

## Distinguish it from

- **Post-mortem:** after the fact, explains real failure. Pre-mortem is before, on an imagined one.
- **Ordinary risk list:** "what might go wrong" — hedged, abstract, optimism intact. The pre-mortem's *assumed certainty of failure* is what unlocks the candid, specific reasons.

## Protocol

```
FRAME:      "The run is over. This failed — completely. Why?"
GENERATE:   list every reason — solo: sweep data / tools / assumptions
            / environment / spec; orchestrating: several agents list
            independently, no shared draft
MERGE:      combine into one deduplicated master list (no triage)
CLUSTER:    group reasons into themes
MITIGATE:   per theme → prevention + early-warning signal + owning step
FOLD IN:    edit the plan; assign each mitigation to a step/agent; set checks
```

Use the companion `premortem-template.md` to run it.

## When to reach for it

- Before executing any significant plan, migration, refactor, or irreversible action — before momentum makes correction expensive.
- When your plan feels suspiciously clean and you are confident on the first pass.

## Failure modes this prevents

- The plan you would never have questioned mid-execution.
- The failure angle you simply never considered because one line of reasoning crowded it out.
- Confident momentum that only meets reality after the output ships.

---
*A skill of the Church of Conceptual Art · whatisthe.churchofconceptualart.org*
