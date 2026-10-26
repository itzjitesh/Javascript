# JavaScript Master Notes — javascript.info

**Purpose:** One evolving revision document. Keep explanations short, use your own examples, add questions asked during learning, and record recurring misunderstandings.
**Primary syllabus:** https://javascript.info/
**Last curriculum check:** 26 October 2026

## Learning rules
- Strong foundations over speed. At 60 minutes/day, full coverage may take longer than one week.
- Follow javascript.info in order; don't mark an article mastered just because it was read.
- Status standard: introduced → practiced independently → explained from memory → retested after a delay.
- Use games, output prediction, debugging, coding exercises, mini-projects and retrieval practice.
- Never copy a solution before trying. Use AI for hints and explanations, then rebuild independently.

## Session 1 — Baseline: values, variables and equality

**Diagnostic:** 3/5 (60%). This is the baseline, not a judgement of ability.

### Core ideas
- A **value** is data; a variable name is a binding through which code refers to a value.
- `const` prevents reassignment of the binding; it does **not** make an object immutable.
- `let` permits reassignment. Prefer `const` unless reassignment is needed.
- The `+` operator adds numbers or concatenates strings depending on operand types.
- `===` compares without type coercion; `==` may convert types, so prefer `===` unless coercion is intentional.
- **Falsy values:** `false`, `0`, `-0`, `0n`, `""`, `null`, `undefined`, and `NaN`.
- Empty arrays (`[]`) and empty objects (`{}`) are truthy in JavaScript.

### Minimal examples
```js
const person = { name: "Jitesh" };
person.name = "J"; // allowed: property mutation
// person = {};   // not allowed: reassigning a const binding

console.log(2 + 2);   // 4
console.log(2 + "2"); // "22" (a string)

console.log(5 === "5"); // false
console.log(5 == "5");  // true (type coercion)

console.log(Boolean([]));  // true
console.log(Boolean({}));  // true
console.log(Boolean(""));  // false
console.log(Boolean(0));   // false
console.log(Boolean("0")); // true
```

### Diagnostic results and weaknesses
- **Q1 — const reassignment:** answered correctly. Keep the distinction between reassignment and object mutation.
- **Q2 — `2 + "2"`:** answered correctly. Result is the string `"22"`, not number `22`.
- **Q3 — falsy values:** missed that an empty array is truthy. Revisit falsy values and Boolean conversion.
- **Q4 — strict equality:** incorrectly judged the statement false. Correct rule: `===` does not coerce operand types.
- **Q5 — const object mutation:** answered correctly. A `const` object can have its properties changed unless separately frozen or otherwise protected.

### Retrieval prompts
1. Why is `Boolean([])` true?
2. What is the difference between `5 === "5"` and `5 == "5"`?
3. What can change on an object declared with `const`, and what cannot?
4. Predict the result **and type** of `2 + "2"`.
5. Name the falsy values without looking at this note.

### Mastery rule
Don't mark this cluster as mastered until you can explain the rules, predict examples with the correct value and type, and solve new examples without notes. Re-test after 1 day, 3 days, and 7 days.

## How future notes will be added
For each session, add: concept → short explanation → minimal example → common pitfall → recall prompt → exercise. Add questions asked by Jitesh and recurring mistakes to the weak-area section. Keep detailed source-specific course wording out; notes should be original and concise.
