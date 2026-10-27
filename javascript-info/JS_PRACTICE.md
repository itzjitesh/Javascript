# JavaScript Practice, Weak Areas & Session Log

This file records performance and targeted follow-up exercises. Add a new session at the top after each learning session.

## Current learning profile
- **Baseline quiz:** 3/5 (60%)
- **Strengths observed:** identified const reassignment error; distinguished string concatenation result; understood that a const object can have its properties mutated.
- **Needs practice:** falsy/truthy values, especially empty arrays; strict vs loose equality and type coercion.
- **Next action:** complete the “Truthy or Falsy?” warm-up and “Equality Detective” challenge before moving to new material.

## Weak-area queue

### W1 — Truthy and falsy values
**Misunderstanding observed:** selected an empty array as falsy.

Remember:
- Falsy: `false`, `0`, `-0`, `0n`, `""`, `null`, `undefined`, `NaN`.
- Most other values are truthy, including `[]`, `{}`, and `"0"`.

Practice without running code first:
1. Predict `Boolean([])`, `Boolean({})`, `Boolean("")`, `Boolean("0")`, `Boolean(NaN)`.
2. Explain why `if ([]) { ... }` executes.
3. Write one condition that handles an empty array correctly; do not rely on truthiness to test whether it has items.

### W2 — Strict equality
**Misunderstanding observed:** answered “false” to the statement that `===` compares without type coercion.

Remember:
- `5 === "5"` is `false`; number and string types differ.
- `5 == "5"` is `true` due to coercion.
- Prefer `===` unless there is a clear, deliberate reason to use `==`.

Practice:
1. Predict `0 === false`, `0 == false`, `null === undefined`, `null == undefined`.
2. Explain each answer by naming the types and whether coercion occurs.

## Session log

### Session 1 — Fundamentals diagnostic (26 October 2026)
- Result: **3/5 (60%)**
- Q1: const reassignment → correct.
- Q2: `2 + "2"` → correct; result is string `"22"`.
- Q3: falsy values → incorrect; empty array is truthy.
- Q4: strict equality → incorrect; `===` does not coerce types.
- Q5: const object mutation → correct; a const binding does not freeze object properties.
- **Follow-up:** W1 and W2 must be retested before marking them mastered.

## Score history
| Session | Focus | Score | Next action |
|---|---|---:|---|
| 1 | Values, variables, coercion, equality | 3/5 (60%) | Retest W1 and W2 |

## Rules for performance tracking
- A quiz score is one signal, not a complete measure of understanding.
- When a topic is missed, add an explanation and a fresh example to `JS_MASTER_NOTES.md`.
- Keep a weakness active until the learner explains it correctly and passes a new problem without hints.
- Re-test weak topics after roughly 1 day, 3 days and 7 days.
- Use new questions in retests; avoid memorizing answers to the same quiz.


### Session 2 — Truthy/falsy and equality retest (27 October 2026)
- Result: **5/5 (100%)** on fresh questions.
- Correctly identified `Boolean("0")` and `Boolean([])` as true.
- Correctly distinguished `0 == false` (true) from `0 === false` (false).
- Correctly recognized that `if ([])` executes and separate empty arrays are not strictly equal.
- Interpretation: immediate recall improved. Do not mark truthiness or equality mastered yet; use harder examples and a delayed retest.

## Updated score history
| Session | Focus | Score | Next action |
|---|---|---:|---|
| 1 | Values, variables, coercion, equality | 3/5 (60%) | Retest weak areas |
| 2 | Fresh truthiness and equality questions | 5/5 (100%) | Test edge cases and delayed recall |
