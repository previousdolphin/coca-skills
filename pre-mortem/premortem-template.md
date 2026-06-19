# Pre-Mortem Worksheet

Plan / task being executed: ____________________________________________

Run date: __________   Agent / orchestrator: __________

---

## 1. The Framing Prompt

State this first, in the past tense, before listing anything:

> "The run is over. I executed everything in this plan — and it failed.
> Completely. The output is wrong, the task is broken, the user is worse
> off. Looking back, I know exactly why it went wrong. List every reason
> it failed."

Do not soften it to "might fail." Assume the failure is certain and finished.

---

## 2. Failure Reasons (enumerate before triaging)

List every reason this failed. Quantity over polish. If solo, sweep each
angle: data · tools · assumptions · environment · the spec itself. If
orchestrating, have several agents list independently, then merge here.

1. ____________________________________________________________
2. ____________________________________________________________
3. ____________________________________________________________
4. ____________________________________________________________
5. ____________________________________________________________
6. ____________________________________________________________
7. ____________________________________________________________
8. ____________________________________________________________
9. ____________________________________________________________
10. ___________________________________________________________

(Merge every reason — across angles, or across agents — into one deduplicated list before triaging.)

---

## 3. Mitigations

Owner = the step or sub-agent responsible for carrying out the prevention during the run.

| Risk (failure reason) | Likelihood (H/M/L) | Prevention / early-warning signal | Owner (step / agent) |
|-----------------------|--------------------|-----------------------------------|----------------------|
|                       |                    |                                   |                      |
|                       |                    |                                   |                      |
|                       |                    |                                   |                      |
|                       |                    |                                   |                      |
|                       |                    |                                   |                      |

---

## 4. Fold Into the Plan

Which mitigations change the plan, and which step or agent owns the change?

- ____________________________________________________________
- ____________________________________________________________
- ____________________________________________________________

A pre-mortem that doesn't edit the plan was theater. Leave coordinates for whoever — agent or human — runs this next.

---
*A skill of the Church of Conceptual Art · whatisthe.churchofconceptualart.org*
