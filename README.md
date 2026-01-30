# README — Learning Path & Engineering Philosophy

## Who I Am

I am a self-taught software engineer who learned, over time, that how I learn and work matters just as much as what I build.

Rather than chasing tools, frameworks, or short-lived trends, I’ve chosen to focus on **foundations, clarity, and sustainability**. My goal is simple: to understand problems deeply, reason about them carefully, and deliver solutions that remain reliable long after the initial excitement fades.

This approach didn’t come from theory. It came from experience—seeing how easily complexity grows when fundamentals are skipped.

---

## How I Learn (High-Level)

Early in my learning journey, I realized that thinking and shipping pull in different directions. Trying to do both at once often leads to shallow understanding and fragile systems.

So I separate them deliberately.

- **Racket** is where I think.
- **Go** is where I ship.

Each language has a clear role, and neither is allowed to replace the other.

---

## Racket — Where Ideas Are Formed

I use Racket, primarily through *How to Design Programs* and *Structure and Interpretation of Computer Programs*, as a space for careful thinking.

In Racket, I focus on:
- defining data precisely,
- making invariants explicit,
- designing total functions,
- reasoning about behavior without worrying about performance or infrastructure.

This is where I slow down and ask:

> “What is the system, really?”

There is no pressure to deliver here. No optimization. No framework gravity.  
The only goal is **clarity and correctness of the model**.

---

## Go — Where Ideas Are Shipped

Once an idea is clear, I move to Go.

Go is where models meet reality: IO, errors, concurrency, and operational constraints. I value Go for its explicitness—control flow is visible, failures are hard to ignore, and the runtime behavior is predictable.

In Go, I focus on:
- explicit control flow,
- visible error handling,
- simple, understandable concurrency,
- minimal reliance on frameworks or hidden magic.

Because Go lacks native algebraic data types, I manually enforce invariants using:
- tagged enums,
- constructor functions,
- explicit state machines,
- defensive `switch` statements with fail-fast behavior.

This is a conscious trade-off. I’m willing to write more code in exchange for **semantic honesty and long-term maintainability**.

---

## Why This Approach

I chose this path for practical reasons.

I have limited daily study time. I care about skills that age well. And I’ve learned that productivity over years depends far more on **clear thinking** than on expressive syntax or clever abstractions.

Many of the hardest bugs I’ve seen came not from complex logic, but from incorrect assumptions that still compiled. My approach is designed to reduce that risk by making assumptions explicit early.

---

## What You Can Expect From My Code

My code tends to be:

- data-first,
- explicit about invariants,
- intentionally boring,
- readable without deep context,
- cautious about hidden behavior.

If something is complex, it’s because the problem itself is complex—not because the solution is trying to be impressive.

---

## What I Intentionally Avoid

During my fundamentals phase, I intentionally avoid:
- framework-driven design,
- abstraction for its own sake,
- excessive metaprogramming,
- copying idioms without understanding the trade-offs.

These tools are useful, but only after the underlying principles are solid.

---

## Current Focus

Right now, I’m focused on:
- deepening core computer science fundamentals,
- translating well-understood models into practical Go services and tools,
- building small systems that are correct, explainable, and resilient.

---

## Closing Note

Over time, I’ve learned that I do my best work in environments that value clarity over novelty and understanding over speed.

I don’t optimize for hype.  
I optimize for **thinking clearly and delivering reliably**.

If your team values strong fundamentals, explicit reasoning, and maintainable systems, we’ll likely work well together.