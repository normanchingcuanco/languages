# 🧠 Master JavaScript Program (Interview-Oriented | Execution-Control First)

---

## 1. Training & Drill Methodology
**Affects:** All Phases

| Guideline | Description | Objective | Purpose |
|------|------|------|------|
| Limited Drills Per Topic | Each concept is practiced using **1–2 drills only** before reviewing results | Prevent overload | Encourage deeper focus on each concept |
| Gradual Difficulty Increase | Drills start simple and increase in complexity slowly | Build stable understanding | Avoid confusion from jumping difficulty levels |
| Topic Stability Rule | Do not introduce new topics until the current topic is clearly understood | Strengthen foundations | Prevent shallow learning gaps |
| Unique Variable Names | New drills must use **different variable names** | Force active code reading | Prevent memorization shortcuts |
| Mock Interview Style | Questions should resemble job-test or interview prompts | Simulate real coding scenarios | Improve job readiness |
| Manual JavaScript Writing | The learner must manually read and write code | Build true coding fluency | Avoid passive pattern copying |
| Step-by-Step Execution | Each answer must trace code execution line by line | Strengthen reasoning about program flow | Improve debugging ability |
| Logic Explanation | Explanations should be written in **beginner-friendly language** with simple steps | Make concepts easier to understand | Reduce confusion while learning |
| Boundary & Precedence Awareness | Drills should include edge cases and priority checks | Improve reliability of solutions | Detect hidden bugs |
| Execution Control First | Focus on control flow and logic before advanced abstractions | Build strong architectural thinking | Prepare for later JavaScript concepts |
| Structured Drill Response | Each drill answer should include **output, step-by-step evaluation, branch identification (if applicable), and boundary tests** | Reinforce disciplined thinking | Ensure full understanding of code behavior |
| Iterative Drill Review | Drills are solved first, then reviewed together before moving forward | Reinforce understanding | Correct misconceptions early |
| Minimal Responses | Explanations and instructions should be concise and focused | Reduce unnecessary scrolling | Keep learning interactions efficient |
| Code-First Explanations | Code examples should remain visible while explanations are given | Maintain clarity while reading logic | Prevent losing context when reviewing solutions |
| Optional Difficulty Escalation | Drills may follow a progression: Binary → Multi-branch → Guard + classification → Interview function → Edge-case defense | Gradually expand logic complexity | Build confidence toward interview-level problems |

---

### Typical Drill Flow

1. A **small number of drills (1–2)** are given for the current topic.  
2. The learner writes the code and explains the result.  
3. The learner provides:
   - Output  
   - Step-by-step evaluation  
   - Explanation of why the result occurs  
4. The solution is **reviewed and corrected if necessary**.  
5. Additional drills may be given with **different variations** to strengthen understanding.  
6. Only when the topic feels stable do we **move to the next concept**.

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

## 8. Current Training Priority
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