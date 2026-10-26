# JavaScript.info Curriculum & Progress Tracker

**Source of checklist:** https://javascript.info/ (official tutorial map)
**Checked:** 26 October 2026
**Scope:** Part 1, Part 2, and Part 3 / Additional articles. We will work through every listed article. Any “More…” link or newly revealed subtopic must be inspected when its section is reached; do not count a section complete until those items are accounted for.

## How to use statuses
- `[ ]` Not started
- `[~]` Introduced / currently learning / needs practice
- `[x]` Mastered: practiced independently, explained from memory, and passed a delayed retest
- A video/article being read is not enough to mark it mastered.

## Dashboard
- **Daily study target:** 60 minutes
- **Current baseline quiz:** 3/5 (60%)
- **Current focus:** truthy/falsy values and strict equality (`===`)
- **Current stage:** opening fundamentals introduced; not yet mastered
- **Session log:** see `JS_PRACTICE.md`
- **Revision notes:** see `JS_MASTER_NOTES.md`

## Part 1 — The JavaScript language

### 1. An introduction
- [ ] An Introduction to JavaScript
- [ ] Manuals and specifications
- [ ] Code editors
- [ ] Developer console

### 2. JavaScript Fundamentals
- [ ] Hello, world!
- [ ] Code structure
- [ ] The modern mode, "use strict"
- [~] Variables — introduced; retest
- [~] Data types — introduced; retest
- [ ] Interaction: alert, prompt, confirm
- [~] Type Conversions — introduced; weak area
- [~] Basic operators, maths — introduced; plus/string behavior practiced
- [~] Comparisons — introduced; strict equality needs retest
- [ ] Conditional branching: if, '?'
- [ ] Logical operators
- [ ] Nullish coalescing operator '??'
- [ ] Loops: while and for
- [ ] The "switch" statement
- [ ] Functions
- [ ] Function expressions
- [ ] Arrow functions, the basics
- [ ] JavaScript specials
- [ ] Inspect all subtopics exposed by the section's "More…" link

### 3. Code quality
- [ ] Debugging in the browser
- [ ] Coding Style
- [ ] Comments
- [ ] Ninja code
- [ ] Automated testing with Mocha
- [ ] Polyfills and transpilers

### 4. Objects: the basics
- [ ] Objects
- [ ] Object references and copying
- [ ] Garbage collection
- [ ] Object methods, "this"
- [ ] Constructor, operator "new"
- [ ] Optional chaining '?.'
- [ ] Symbol type
- [ ] Object to primitive conversion

### 5. Data types
- [ ] Methods of primitives
- [ ] Numbers
- [ ] Strings
- [ ] Arrays
- [ ] Array methods
- [ ] Iterables
- [ ] Map and Set
- [ ] WeakMap and WeakSet
- [ ] Object.keys, values, entries
- [ ] Destructuring assignment
- [ ] Date and time
- [ ] JSON methods, toJSON
- [ ] Inspect all subtopics exposed by the section's "More…" link

### 6. Advanced working with functions
- [ ] Recursion and stack
- [ ] Rest parameters and spread syntax
- [ ] Variable scope, closure
- [ ] The old "var"
- [ ] Global object
- [ ] Function object, NFE
- [ ] The "new Function" syntax
- [ ] Scheduling: setTimeout and setInterval
- [ ] Decorators and forwarding, call/apply
- [ ] Function binding
- [ ] Arrow functions revisited
- [ ] Inspect all subtopics exposed by the section's "More…" link

### 7. Object properties configuration
- [ ] Property flags and descriptors
- [ ] Property getters and setters

### 8. Prototypes, inheritance
- [ ] Prototypal inheritance
- [ ] F.prototype
- [ ] Native prototypes
- [ ] Prototype methods, objects without __proto__

### 9. Classes
- [ ] Class basic syntax
- [ ] Class inheritance
- [ ] Static properties and methods
- [ ] Private and protected properties and methods
- [ ] Extending built-in classes
- [ ] Class checking: instanceof
- [ ] Mixins

### 10. Error handling
- [ ] Error handling, try...catch
- [ ] Custom errors, extending Error

### 11. Promises, async/await
- [ ] Introduction: callbacks
- [ ] Promise
- [ ] Promises chaining
- [ ] Error handling with promises
- [ ] Promise API
- [ ] Promisification
- [ ] Microtasks
- [ ] Async/await

### 12. Generators, advanced iteration
- [ ] Generators
- [ ] Async iteration and generators

### 13. Modules
- [ ] Modules, introduction
- [ ] Export and Import
- [ ] Dynamic imports

### 14. Miscellaneous
- [ ] Proxy and Reflect
- [ ] Eval: run a code string
- [ ] Currying
- [ ] Reference Type
- [ ] BigInt
- [ ] Unicode, String internals
- [ ] WeakRef and FinalizationRegistry

## Part 2 — Browser: Document, Events, Interfaces

### 1. Document
- [ ] Browser environment, specs
- [ ] DOM tree
- [ ] Walking the DOM
- [ ] Searching: getElement*, querySelector*
- [ ] Node properties: type, tag and contents
- [ ] Attributes and properties
- [ ] Modifying the document
- [ ] Styles and classes
- [ ] Element size and scrolling
- [ ] Window sizes and scrolling
- [ ] Coordinates
- [ ] Inspect all subtopics exposed by the section's "More…" link

### 2. Introduction to Events
- [ ] Introduction to browser events
- [ ] Bubbling and capturing
- [ ] Event delegation
- [ ] Browser default actions
- [ ] Dispatching custom events

### 3. UI Events
- [ ] Mouse events
- [ ] Moving the mouse: mouseover/out, mouseenter/leave
- [ ] Drag'n'Drop with mouse events
- [ ] Pointer events
- [ ] Keyboard: keydown and keyup
- [ ] Scrolling

### 4. Forms, controls
- [ ] Form properties and methods
- [ ] Focusing: focus/blur
- [ ] Events: change, input, cut, copy, paste
- [ ] Forms: event and method submit

### 5. Document and resource loading
- [ ] Page: DOMContentLoaded, load, beforeunload, unload
- [ ] Scripts: async, defer
- [ ] Resource loading: onload and onerror

### 6. Miscellaneous
- [ ] Mutation observer
- [ ] Selection and Range
- [ ] Event loop: microtasks and macrotasks

## Part 3 — Additional articles

### 1. Frames and windows
- [ ] Popups and window methods
- [ ] Cross-window communication
- [ ] The clickjacking attack

### 2. Binary data, files
- [ ] ArrayBuffer, binary arrays
- [ ] TextDecoder and TextEncoder
- [ ] Blob
- [ ] File and FileReader

### 3. Network requests
- [ ] Fetch
- [ ] FormData
- [ ] Fetch: Download progress
- [ ] Fetch: Abort
- [ ] Fetch: Cross-Origin Requests
- [ ] Fetch API
- [ ] URL objects
- [ ] XMLHttpRequest
- [ ] Resumable file upload
- [ ] Long polling
- [ ] WebSocket
- [ ] Server Sent Events
- [ ] Inspect all subtopics exposed by the section's "More…" link

### 4. Storing data in the browser
- [ ] Cookies, document.cookie
- [ ] LocalStorage, sessionStorage
- [ ] IndexedDB

### 5. Animation
- [ ] Bezier curve
- [ ] CSS-animations
- [ ] JavaScript animations

### 6. Web components
- [ ] From the orbital height
- [ ] Custom elements
- [ ] Shadow DOM
- [ ] Template element
- [ ] Shadow DOM slots, composition
- [ ] Shadow DOM styling
- [ ] Shadow DOM and events

### 7. Regular expressions
- [ ] Patterns and flags
- [ ] Character classes
- [ ] Unicode: flag "u" and class `\\p{...}`
- [ ] Anchors: string start ^ and end $
- [ ] Multiline mode of anchors ^ $, flag "m"
- [ ] Word boundary: `\\b`
- [ ] Escaping, special characters
- [ ] Sets and ranges [...]
- [ ] Quantifiers +, *, ? and {n}
- [ ] Greedy and lazy quantifiers
- [ ] Capturing groups
- [ ] Backreferences in pattern: \\N and \\k<name>
- [ ] Alternation (OR) |
- [ ] Lookahead and lookbehind
- [ ] Catastrophic backtracking
- [ ] Sticky flag "y", searching at position
- [ ] Methods of RegExp and String
- [ ] Inspect all subtopics exposed by the section's "More…" link

## Completion criteria
For every article: read it, explain the concept in your own words, solve its tasks or a similar exercise, record mistakes, and pass a later retrieval check. We will use mini-projects and mixed reviews after each major section. Coverage is complete only after all listed items and expandable "More…" entries have been accounted for.
