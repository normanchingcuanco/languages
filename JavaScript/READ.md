# 🧠 Master JavaScript Program (Interview-Oriented | Execution-Control First)

---

## 1. Training Rules
**Affects:** All Phases

| Feature Name | Description | Objective | Purpose |
|------|------|------|------|
| 1–3 Drills Per Topic | Limit each concept to a small number of drills | Prevent overload | Encourage deep mastery per concept |
| Gradual Difficulty Increase | Move from easier drills to harder drills slowly | Build stable understanding | Avoid logical confusion |
| No New Topics Until Stable | Do not introduce new topics until the current one is strong | Strengthen foundations | Prevent shallow learning |
| Unique Variable Names | Do not reuse variable names between drills | Force active reading | Prevent memorization shortcuts |
| Mock Interview Questions | Use job-test style problem descriptions | Simulate technical interviews | Improve job readiness |
| Manual JavaScript Writing | You must personally write and read the code | Build coding fluency | Avoid passive pattern copying |
| Step-by-Step Evaluation | Trace each condition and result | Strengthen execution reasoning | Improve debugging ability |
| Explain Logic | Explain why a solution works or fails | Build reasoning discipline | Prevent guessing answers |
| Detect Boundaries & Precedence | Always check edge cases and operator priority | Improve reliability | Prevent hidden bugs |
| Execution Control First | Master control flow before abstraction | Build architecture thinking | Prepare for advanced JS patterns |

---

## 2. Phase 1 — Foundations (Core Mechanics)
**Affects:** Core JavaScript Execution

| Feature Name | Description | Objective | Purpose | Build Status |
|------|------|------|------|------|
| Variables | `let`, `const`, declaration vs initialization, reassignment, accidental globals, `undefined`, `null`, `typeof` | Understand value storage | Control state and memory | ✅ Complete |
| Data Types | Primitives, objects, arrays, functions, mutation vs reassignment | Understand different data behaviors | Prevent incorrect manipulation | ✅ Complete |
| Scope | Global scope, function scope, block scope, shadowing | Control variable visibility | Prevent scope bugs | ✅ Complete |
| Operators | Arithmetic, comparison, logical, short-circuit behavior, operator precedence, assignment vs comparison trap | Understand expression evaluation | Improve boolean accuracy | ✅ Complete |
| Conditionals | `if`, `if / else`, truthy vs falsy, explicit comparisons, parentheses grouping | Build branching logic | Prepare for decision systems | ✅ Complete |

---

## 3. Phase 2 — Control Flow & Logical Discipline
**Affects:** Decision Architecture

| Feature Name | Description | Objective | Purpose | Build Status |
|------|------|------|------|------|
| Binary Branching | `if`, `if / else`, exclusive branching | Learn simple two-path logic | Build correct branching habits | ✔ Strong |
| Multi-Branch Systems | `if / else if / else`, range classification, branch ordering | Build structured decision trees | Prevent unreachable logic | 🟡 In Progress |
| Guard Architecture | Type validation, range validation, fail-fast pattern | Reject invalid inputs early | Protect business logic | 🟡 Practicing |
| Logical Pitfalls | Assignment in condition, truthy traps, boundary failures, OR rescue logic, `&&` short-circuit | Detect logical mistakes | Improve debugging | ✔ Strong |
| Decision Tree Debugging | Identify which rule broke logic, reorder branches, clean prioritization | Repair broken condition trees | Strengthen architecture thinking | 🟡 Needs Repetition |
| First-Match Priority | First true condition in `if / else if` chain executes and stops | Understand execution stopping | Prevent branch shadowing | 🟡 Practicing |
| Guard Layering | Validate invalid input before classification | Separate validation from logic | Improve program safety | 🟡 Practicing |
| Descending Classification | Order classification thresholds from highest to lowest | Use progressive elimination | Build clean range logic | 🟡 Practicing |

---

## 4. Phase 3 — Interview-Focused Functional Programming
**Affects:** Interview-Style Problem Solving

| Feature Name | Description | Objective | Purpose | Build Status |
|------|------|------|------|------|
| Function Contracts | Parameters, arguments, return values, early return, returning `undefined`, pure vs impure functions | Understand how functions return results | Build correct interview solutions | ⬜ Not Trained |
| Array Methods | `filter`, `map`, `reduce`, `some`, `every`, `find`, `includes` | Transform and search data | Solve modern JS problems | ⬜ Not Trained |
| Arrow Functions | `=>`, implicit return, explicit return, callbacks | Learn modern function syntax | Support functional patterns | ⬜ Not Trained |
| String Processing | `toLowerCase`, `trim`, `includes`, `length` | Handle text operations | Support search problems | 🟡 Light Exposure |
| Object Array Searching | Pattern: `isUserValid(users, username, password)` | Search structured datasets | Prepare for real interview problems | ⬜ Not Trained |

---

## 5. Sample Interview Question Formats
**Affects:** Drill Format

| Feature Name | Description | Objective | Purpose |
|------|------|------|------|
| Blog Search Question | // Question #1: Create a function that takes an array of blog post titles and a keyword. Search must be case-insensitive. Return undefined if inputs are not expected types. | Practice defensive function logic | Train interview-style problem solving |
| User Validation Question | // Question #2: Given an array of user objects containing username and password, write isUserValid(users, username, password). Return true if match exists, false otherwise. | Practice object array searching | Train authentication logic problems |
| Constraint Reading | Identify input data, number of inputs, limitations, and boundaries before coding | Train problem analysis | Prevent rushed coding |

---

## 6. Drill Design Structure
**Affects:** Practice Sessions

| Feature Name | Description | Objective | Purpose |
|------|------|------|------|
| Question Header | Problem description, constraints, expected behavior | Understand task before coding | Prevent incorrect assumptions |
| Starter Code | Base function with variables provided | Focus on writing logic | Reduce setup time |
| Required Response | Output, step-by-step evaluation, branch execution, boundary tests | Build execution reasoning | Improve debugging clarity |
| Escalation Pattern | Binary → Multi-branch → Guard + classification → Interview function → Edge-case defense | Increase difficulty gradually | Build structured learning path |

---

## 7. Starter Code Template
**Affects:** Drill Implementation

Example starter template used in drills:

```javascript
function exampleYY() {
   // variables provided
   // you write logic
}

````

---

## 8. Required Response Format
**Affects:** Drill Answers

When responding to a drill, your answer should include the following elements:

**Output Display**  
Show the program result to confirm what the code produced.

**Step-by-Step Evaluation**  
Trace each condition and evaluation step-by-step to explain how the result was reached.

**Branch Identification**  
Identify which branch executed in the decision structure.

**Boundary Tests**  
Test edge values and limits to confirm the logic behaves correctly and does not produce hidden bugs.

---

## 9. Escalation Pattern
**Affects:** Difficulty Progression

This is an optional pattern used to gradually increase the difficulty of drills.

| Level | Description |
|------|------|
| Level 1 — Binary Condition | Simple `if / else` decisions to practice basic branching control. |
| Level 2 — Multi-Branch | `if / else if / else` classification to train decision trees and range logic. |
| Level 3 — Guard + Classification | Validate inputs first, then classify results to build safe control flow. |
| Level 4 — Interview Function | Solve a full problem using a function to simulate interview-style tasks. |
| Level 5 — Edge Case Defense | Add validation for invalid inputs and boundary cases to build defensive programming habits. |

---

## 10. Current Training Priority
**Affects:** Immediate Learning Direction

| Feature Name | Description | Objective | Purpose | Build Status |
|------|------|------|------|------|
| Phase 2 Stability | Reinforce control-flow architecture | Make decision systems automatic | Prepare for functional programming | 🟡 Active |
| First-Match Priority | Practice branch ordering discipline | Prevent unreachable branches | Improve logic clarity | 🟡 Active |
| Guard Layering | Validate inputs before classification | Separate validation and logic | Improve program safety | 🟡 Active |
| Descending Classification | Order thresholds highest → lowest | Build clean range logic | Simplify multi-branch systems | 🟡 Active |

---

### Advancement Rule

Phase 3 begins **only when Phase 2 control flow feels automatic.**