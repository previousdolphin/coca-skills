---
name: coding-with-judgment
description: Use when starting a feature, fix, or refactor — to write code that is simple, honest, and verified instead of clever, speculative, or untested.
category: By Use Case
---

# Coding with Judgment

Most bad code is not wrong; it is premature. It solves problems no one has yet, abstracts patterns that have appeared once, and reports success it never checked. Judgment is mostly restraint applied at the right moment. The readymade principle: do the simplest thing that works, and stop.

## The moves

1. **Do the simplest thing that works.** Write the most direct code that solves the actual problem in front of you. Indirection, configuration, and flexibility are costs you pay now for a future that may never arrive. Reach for the boring solution first.

2. **Don't abstract until ~3 real examples.** One use is a function. Two uses might be coincidence. Around the third genuine, concrete instance, the shape of the abstraction is finally visible — and only then is it safe to extract. Generalizing earlier means designing for a pattern you are guessing at, and the guess is usually wrong.

3. **Respect Chesterton's fence.** Before deleting code, a flag, a check, or a workaround, understand *why* it exists. If you cannot explain what it was for, you are not yet qualified to remove it. Find the commit, the ticket, or the person. The ugly line is often load-bearing.

4. **Find the question beneath the bug.** The symptom is rarely the failure. A null where you expected a value is a *report*, not a *cause*. Trace upstream to the actual broken assumption. Patching the symptom moves the bug; fixing the cause removes it.

5. **Don't handle states that can't happen.** Defensive code for impossible inputs adds noise, hides real logic, and silently swallows the bugs that would have told you your model was wrong. Let impossible states fail loudly. Validate at the boundary; trust the interior.

6. **Verify before claiming done — congruence.** "Done" means you ran it and watched it work, not that you wrote code that should work. If you did not verify, say exactly that: "written, not yet run." Report what actually failed, faithfully — never round a partial pass up to success. An honest "it's broken here" is worth more than a confident "it works."

## The question beneath

When you feel the urge to add a layer, ask: *what problem do I have right now, today, that this solves?* If the answer is "a problem I imagine I might have," do not build it. Write a note instead and move on.

## Compact protocol
```
[ ] Solving the real problem, not an imagined future one
[ ] Simplest direct implementation chosen first
[ ] No abstraction extracted before ~3 concrete uses
[ ] Understood why existing code exists before changing/deleting it
[ ] Traced the bug to its cause, not just its symptom
[ ] No error handling for states that cannot occur
[ ] Ran it and observed it work before saying "done"
[ ] Reported failures and unverified parts honestly
```

---
*A skill of the Church of Conceptual Art · whatisthe.churchofconceptualart.org*
