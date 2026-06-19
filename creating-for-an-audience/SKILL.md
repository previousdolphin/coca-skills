---
name: creating-for-an-audience
description: Use anytime you produce output for a reader who isn't you — a report, answer, doc, code, or data — to build for the reader's context instead of your own.
category: By Use Case
---

# Creating for an Audience

You are an agent producing a deliverable, and someone else has to use it. That someone may be a human — or another agent or system downstream that takes your output as its input. The default failure is to produce what satisfies *you*, the maker: you hold the full task context, so you write into it, and the reader, who has none of it, falls through the gaps. Audience-first creation reverses the order: start from whoever (or whatever) is on the other end and work back to the artifact.

## The moves

1. **Know the reader.** Name them concretely: are they a person or a machine? Their role, what they already know, what context they already have, what they care about, how much attention or token budget they will spend. If the reader is a downstream agent, that means its task, its input schema, and what it cannot infer on its own. "General audience" is not a reader; it is an excuse. If you cannot picture one specific recipient, you do not yet know enough to create.

2. **Name the change you want.** What should be different in the reader after they consume this — what will they know, decide, or be able to do that they could not before? For a human: an informed decision, an action taken. For a downstream agent: a field it can now parse, a branch it can now take. If you cannot state the intended change in one sentence, the deliverable has no target and will hit nothing.

3. **Ask what they're hiring it to do (jobs-to-be-done).** The reader doesn't want your output; they want the progress it makes possible. Find the job: what is the reader trying to get done that this deliverable is the tool for? A summary is hired to let someone skip the original; a function is hired to be called without reading its body; an API response is hired to be acted on, not admired. Build for the job, not for the parts you found interesting to produce.

4. **Leave coordinates (the Generational Clause).** Assume the reader arrives with *zero* prior context — a person reading this cold, or a downstream agent that never saw your reasoning, your prompt, or your earlier steps. Ground every abstraction in a concrete example or value. State your framing explicitly instead of assuming it is shared. Define the terms you lean on; resolve the references ("it", "the above") that only make sense inside your own chain of thought. Enough context that a stranger — or a fresh agent — can reconstruct your meaning is the difference between a record and a residue.

5. **Set and meet expectations.** Lead with the point so the reader knows where they are going before they invest in getting there. Then deliver in the order you promised, in the shape the reader needs — prose for a person, the agreed structure or schema for a system. Surprise is for the content, never for the structure: a reader lost in the architecture cannot receive the substance, and a downstream parser given an unexpected shape simply breaks.

6. **Test for clarity with a stranger.** The acceptance test: could a fresh agent or a person, with none of your context, consume this once, state your main point in a single sentence, and name the next step they should take? If not, you have written for yourself. Revise toward the stranger.

## The question beneath

Before you ask "what do I want to output," ask "what does the reader need, and where are they standing when they meet this?" The first question produces a monologue; the second produces something usable.

## Compact protocol
```
[ ] One specific reader named (human or agent; role, context, attention/budget)
[ ] Intended change in the reader stated in one sentence
[ ] The job the reader is hiring this to do is named
[ ] Coordinates left: zero-context reader assumed; abstractions grounded; references resolved
[ ] Framing and key terms stated explicitly, not assumed shared
[ ] Point comes first; structure/shape is what the reader expects
[ ] Stranger test passed: a fresh agent/person gets the main point in one sentence + the next step
```

---
*A skill of the Church of Conceptual Art · whatisthe.churchofconceptualart.org*
