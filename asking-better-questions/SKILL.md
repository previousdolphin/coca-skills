---
name: asking-better-questions
description: Use before answering a request, writing a plan, or invoking a tool — especially when the stated question feels obvious, urgent, or you're about to optimize something. Surfaces the real question beneath the asked one, stress-tests working frames, and prevents the most common failure: solving the wrong problem quickly. A reasoning discipline from the Church of Conceptual Art's "Asking Better Questions" method.
category: Thinking Frameworks
---

# Asking Better Questions

AI does not make bad thinking good. It makes thinking *faster* — so bad thinking gets worse faster, and good thinking becomes a genuine advantage. The scarce resource is not output; it is clarity. This skill is a discipline for finding the right question before spending effort on an answer.

Use it at the start of any non-trivial task, and again whenever a solution starts "working" (that is the most dangerous moment).

## The five moves

Run these in order. Most of the value is in moves 1 and 2.

### 1. Find the question beneath the question
The stated question almost always carries a buried assumption. Before answering, ask:
- What is this question taking for granted?
- What would change if I inverted it?
- If I answered this perfectly, would it actually solve the underlying problem — or just the symptom?

Then state the real question in one sentence: *"The question beneath this is…"* Answer **that** one.

### 2. Run a Perpetual Dissolution check
"Today's liberating insight is tomorrow's jail of stale contentment." When a frame is working, audit it:
- What assumption has this frame quietly hardened into a rule?
- What constraint is it enforcing invisibly?
- If I had to dismantle this in six months, what would I wish I'd left flexible?

Hold the best idea lightly enough that it can still change.

### 3. Audit your thinking before you reach for the tool
The prompt is never the problem; the thinking behind it is. Before generating, searching, or calling a tool:
- Am I using the tool to *clarify* my thinking, or to *avoid* it?
- Is the input a good question, or just a fast one?

If the thinking isn't clear, fix the question, not the prompt.

### 4. Think in systems, not outputs
Design for failure modes, not just the happy path:
- Where will this break, and will the break be visible?
- What forcing function makes me re-evaluate as conditions change?
- Am I optimizing the output, or the outcome the output is supposed to serve?

### 5. Work in the open; let being challenged change the frame
State your current framing plainly and invite it to be challenged — by the user, by another agent, or by your own adversarial pass. Check the result against the *reframed* question from move 1 — not the original. Reasoning that never turns is just assertions placed in sequence.

## A compact protocol you can run inline

```
SURFACE:   the question as asked
ASSUMPTION: what it takes for granted
INVERSION:  what changes if the opposite is true
REAL Q:     the question beneath, in one sentence
TEST:       answering the REAL Q solves the actual problem? (y/n)
DISSOLVE:   one assumption in my current frame to hold loosely
```

If `TEST` is "no," you have found a different problem to solve. That is the win.

## When NOT to over-apply
For genuinely trivial or fully-specified requests ("what's the capital of France"), skip it — running the protocol on a lookup wastes the user's time. The discipline is for ambiguous, high-stakes, or "obvious" requests where the cost of solving the wrong thing is high.

---
*A skill of the Church of Conceptual Art · whatisthe.churchofconceptualart.org*
