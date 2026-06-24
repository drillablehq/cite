---
description: Audit the solution you just produced — check its claims against drillable and report what holds, what's corrected, and what's unverifiable.
---
**Audit your last solution against drillable.** Do not re-solve — review what you just produced.

1. **Extract the checkable claims** from your solution — the numbers, rules, definitions, "X is Y" assertions, dependency/version claims, and design choices that rest on a fact.
2. **Run each through drillable** (verify / search / lookup; for dependencies, the check path). One claim at a time.
3. **Report a verdict per claim**, with its citation:
   - ✅ **verified** — the corpus confirms it (cite the record).
   - ⚠️ **corrected** — the corpus says otherwise (give the right answer + source). **These are the catches — surface them prominently.**
   - ◌ **no record** — the corpus can't ground it; mark it an unverified assumption, never assert it as checked.
4. **End with the list of corrections and unverified assumptions** — the things to fix or double-check before relying on this solution.

Be honest: only audit claims actually in the solution (don't invent claims to grade), and an honest "no record" is a real outcome, not a failure.
