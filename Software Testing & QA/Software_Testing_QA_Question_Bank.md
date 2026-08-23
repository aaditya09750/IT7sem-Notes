# Software Testing and Quality Assurance (STQA)
## Semester VII - Mumbai University (R-19 C-Scheme) | Subject Code: 42676 (DLOC III)

---

## Table of Contents
- [1. Question Frequency and Priority Overview](#1-question-frequency-and-priority-overview)
- [2. Section 1: 5-Mark Questions (Ranked by Frequency)](#2-section-1-5-mark-questions-ranked-by-frequency)
  - [2.1 Repeated Topics (5-Mark Slots)](#21-repeated-topics-5-mark-slots)
  - [2.2 Single Appearance Questions](#22-single-appearance-questions)
- [3. Section 2: 10-Mark Questions (Ranked by Frequency)](#3-section-2-10-mark-questions-ranked-by-frequency)
  - [3.1 Repeated in 100% of Exam Papers (Must Solve)](#31-repeated-in-100-of-exam-papers-must-solve)
  - [3.2 Core High-Yield 10-Mark Questions & Numericals](#32-core-high-yield-10-mark-questions--numericals)
- [4. Section 3: Step-by-Step Solved Programs and Quality Blueprints](#4-section-3-step-by-step-solved-programs-and-quality-blueprints)
  - [4.1 How to Draw DD-Graphs and Calculate Cyclomatic Complexity V(G)](#41-how-to-draw-dd-graphs-and-calculate-cyclomatic-complexity-vg)
  - [4.2 How to Calculate Defect Spoilage Step-by-Step](#42-how-to-calculate-defect-spoilage-step-by-step)
  - [4.3 Boundary Value Analysis (BVC) and Robust Test Case Design](#43-boundary-value-analysis-bvc-and-robust-test-case-design)
  - [4.4 McCall's Software Quality Model Made Simple](#44-mccalls-software-quality-model-made-simple)
  - [4.5 Bug Life Cycle State Machine Diagram](#45-bug-life-cycle-state-machine-diagram)
- [5. Section 4: 3-Hour Exam Strategy](#5-section-4-3-hour-exam-strategy)

---

## 1. Question Frequency and Priority Overview

This overview covers the recurring questions from the previous year question papers.

| Rank | Topic / Question | Typical Marks | Recurrence Rate | Priority Level |
| :---: | :--- | :---: | :---: | :--- |
| 1 | DD-Graph, Cyclomatic Complexity V(G) & Independent Paths | 10M | 100% | Must Prepare First |
| 2 | Agile Testing Life Cycle (ATLC) & Challenges | 10M | 100% | Must Prepare First |
| 3 | Mutation Testing: Primary vs Secondary Mutants & Score | 5M / 10M | 100% | Must Prepare First |
| 4 | Test Automation Selection Criteria (Static vs Dynamic Tools) | 5M / 10M | 100% | Must Prepare First |
| 5 | Structure of Testing Group & Test Management Hierarchy | 5M / 10M | 100% | Must Prepare First |
| 6 | Defect Spoilage Table Calculation (Numerical) | 10M | High Yield | Must Prepare First |
| 7 | Boundary Value Analysis (BVC) & Robust Testing Tables | 10M | High Yield | Must Prepare First |
| 8 | McCall's Software Quality Factors and 3 Pillars | 10M | High Yield | High Priority |
| 9 | Bug Life Cycle: States, Transitions & Diagram | 10M | High Yield | High Priority |
| 10 | Test Suite Prioritization Process and Types | 10M | High Yield | High Priority |
| 11 | ISO 9000:2000 Quality Management Standard | 10M | Standard | Medium Priority |
| 12 | Six Sigma Quality Standard (DMAIC / 3.4 DPMO) | 5M | Standard | Medium Priority |
| 13 | Bottom-Up Integration Testing with Test Drivers | 5M | Standard | Medium Priority |
| 14 | Software Testing Terminology (Error, Defect, Bug, Failure, Oracle) | 5M | Standard | Medium Priority |
| 15 | Performance Testing Importance (Load, Stress, Endurance) | 10M | Standard | Medium Priority |

---

## 2. Section 1: 5-Mark Questions (Ranked by Frequency)

### 2.1 Repeated Topics (5-Mark Slots)

#### Question 5M-01: Mutation Testing (Primary vs Secondary Mutants & Mutation Score)
- **Exam Appearances**: QP Code 15346 (Q.1b), QP Code 28365 (Q.5a)
- **Verbatim Question**: "What is Mutation testing? Differentiate between primary and secondary mutants. Explain primary mutant with an example. (05)"

**Simple Concept Summary for Students:**
- **What is Mutation Testing?** A fault-based testing technique where small bugs (mutations) are deliberately introduced into the program source code to see if test cases can catch and "kill" them.
- **Primary Mutant**: A single syntactic change made to the code (e.g. changing `if (a > b)` to `if (a < b)`).
- **Secondary (Higher-Order) Mutant**: Two or more mutations introduced into the same program simultaneously.
- **Mutation Score Formula**:
  $$\text{Mutation Score} = \frac{D}{N - E} \times 100\%$$
  - $D$ = Number of Mutants Killed (detected by test cases).
  - $N$ = Total Mutants Created.
  - $E$ = Equivalent Mutants (mutants that produce identical output to original program).

#### Question 5M-02: Test Automation Tool Selection Criteria
- **Exam Appearances**: QP Code 15346 (Q.1c), QP Code 28365 (Q.4b)
- **Verbatim Question**: "What criteria you will consider for selection of test tools for automation Testing? (05)"

**Key Selection Criteria to Write in Exam:**
1. **Application Compatibility**: Supports target tech stack (web browsers, mobile OS, desktop).
2. **Ease of Test Authoring**: Supports low-code/scriptless testing as well as standard languages (Java, Python).
3. **CI/CD Integration**: Connects with Jenkins, GitHub Actions, and test management tools (Jira).
4. **Maintenance & Reporting**: Provides detailed execution reports and screenshots of failure points.
5. **Total Cost of Ownership**: Licensing costs vs open-source community support.

#### Question 5M-03: Structure of Testing Group & Test Management
- **Exam Appearances**: QP Code 15346 (Q.1d), QP Code 28365 (Q.3b)
- **Verbatim Question**: "Explain structure of testing Group. What are the key elements of Test Management? (05)"

**Testing Hierarchy Structure:**
- **Test Director / QA Manager**: Sets testing policies and budgets.
- **Test Lead**: Plans test schedule, assigns test cases, and tracks defect metrics.
- **Test Engineers / Automation Developers**: Writes test scenarios, automates test scripts, and logs bugs.

---

### 2.2 Single Appearance Questions

- **Testing Terminology** (QP 15346 Q.1a):
  - *Error*: Human mistake made during coding.
  - *Fault / Defect / Bug*: Manifestation of an error in the software code.
  - *Failure*: Inability of the software system to perform its required function during execution.
  - *Testware*: All artifacts produced during testing (test plans, test scripts, test data).
  - *Test Oracle*: The expected source of truth used to determine if a test passed or failed.
- **Six Sigma Quality Standard** (QP 15346 Q.1e): Focuses on defect reduction to achieve $\le 3.4$ Defects Per Million Opportunities (DPMO). Uses the DMAIC methodology (Define, Measure, Analyze, Improve, Control).
- **Bottom-Up Integration Testing** (QP 28365 Q.1a): Low-level individual modules are tested first, using temporary "Test Drivers" to simulate higher-level calling functions.
- **Testing Simple Loops** (QP 28365 Q.1b): Test 7 scenarios: Skip loop entirely ($n=0$), pass once ($n=1$), pass twice ($n=2$), typical passes ($n=m$), boundary passes ($n=n_{\max}-1$, $n=n_{\max}$), and attempt out-of-bounds ($n=n_{\max}+1$).
- **Statement Coverage Criteria** (QP 28365 Q.1c): Measures the percentage of executable code statements traversed by the test suite: $\text{Statement Coverage} = \frac{\text{Statements Executed}}{\text{Total Executable Statements}} \times 100\%$.
- **State Table Based Testing** (QP 28365 Q.1d): Maps system states against input events in a tabular matrix to verify valid state transitions and catch illegal state transitions.
- **Bugzilla Defect Tracking Tool** (QP 28365 Q.1e): Open-source bug tracking system with automated email alerts, bug lifecycle workflows, search queries, and attachment support.

---

## 3. Section 2: 10-Mark Questions (Ranked by Frequency)

---

### 3.1 Repeated in 100% of Exam Papers (Must Solve)

#### Question 10M-01: Control Flow DD-Graph, Cyclomatic Complexity, and Basis Paths
- **Exam Appearances**: QP Code 15346 (Q.4b), QP Code 28365 (Q.2a & Q.4a)
- **Verbatim Question**: "Consider C code for Prime Number / Factorial. Draw DD graph, calculate cyclomatic complexity, list out independent paths and design test cases. (10)"

**3 Methods to Calculate Cyclomatic Complexity $V(G)$:**
1. **Predicate / Decision Nodes Method**: $V(G) = P + 1$ (where $P$ is the number of decision points like `if`, `while`, `for`).
2. **Edges and Nodes Formula**: $V(G) = E - N + 2P$ (where $E$ = edges, $N$ = nodes, $P$ = connected components = 1).
3. **Enclosed Regions Method**: $V(G) = \text{Number of Enclosed Regions} + 1$.

#### Question 10M-02: Agile Testing Life Cycle (ATLC) & Challenges
- **Exam Appearances**: QP Code 15346 (Q.2b), QP Code 28365 (Q.2b)
- **Verbatim Question**: "Explain Agile Testing Life Cycle and its challenges. What is Agile testing? (10)"

**4 Phases of Agile Testing Life Cycle:**
1. **Impact Assessment**: Gathering user stories and technical inputs from stakeholders during sprint planning.
2. **Agile Test Planning**: Defining test scope, estimating story points, and preparing the test environment.
3. **Release Readiness / Execution**: Executing automated unit tests, story acceptance tests, and exploratory tests during the sprint.
4. **Daily Scrums & Retrospectives**: Daily defect triage, sprint retrospectives to analyze test bottlenecks.

**Key Agile Testing Challenges**: Incomplete/shifting requirements, lack of comprehensive documentation, continuous regression testing load, tight sprint deadlines.

#### Question 10M-03: Test Automation: Need and Static vs Dynamic Tools
- **Exam Appearances**: QP Code 15346 (Q.4a), QP Code 28365 (Q.4b)
- **Verbatim Question**: "What is the need of automation testing activities? Differentiate between static and dynamic tools. (10)"

---

### 3.2 Core High-Yield 10-Mark Questions & Numericals

- **Defect Spoilage Table Calculation** (QP 15346 Q.2a): Solved numerical calculating defect discovery delays across SDLC phases.
- **Boundary Value Analysis (BVC) and Robust Testing for $[1, 100]$** (QP 15346 Q.3a): Design test cases for 3 input variables using Single Fault Assumption.
- **Software Measurement & Types of Software Metrics** (QP 15346 Q.3b): Product metrics (size, complexity), Process metrics (defect removal efficiency), Project metrics (effort, schedule variance).
- **Test Plan Components & Hierarchy** (QP 15346 Q.5a): IEEE 829 Standard test plan structure: Identifier, Introduction, Test Items, Features to be tested, Pass/Fail criteria, Deliverables, Schedule.
- **McCall's Software Quality Factors** (QP 15346 Q.5b): 3 Quality Pillars: Product Operation, Product Revision, and Product Transition.
- **Bug Life Cycle (States & Transitions)** (QP 15346 Q.6a): Lifecycle transitions: New -> Assigned -> Open -> Fixed -> Retest -> Verified -> Closed (or Reopened / Deferred).
- **Effective vs Exhaustive Testing** (QP 15346 Q.6b): Explaining why testing all possible input combinations is mathematically impossible, and how equivalence partitioning and risk-based testing achieve effective coverage.
- **Test Suite Prioritization** (QP 28365 Q.3a): Ordering test cases to maximize early fault detection rate (APFD metric) using business priority, risk level, or code coverage.
- **Bug Classification Across SDLC** (QP 28365 Q.5b): Requirement defects, Architectural defects, Coding syntax/logic bugs, Integration bugs.
- **ISO 9000:2000 Standard** (QP 28365 Q.6a): Principles of Quality Management: Customer focus, Process approach, Continual improvement, Evidence-based decision making.
- **Performance Testing Importance & Types** (QP 28365 Q.6b): Load testing (expected user traffic), Stress testing (breaking point limits), Endurance testing (memory leaks over 48 hours), Spike testing (sudden traffic surges).

---

## 4. Section 3: Step-by-Step Solved Programs and Quality Blueprints

### 4.1 How to Draw DD-Graphs and Calculate Cyclomatic Complexity V(G)

**Given C Code for Prime Number (QP 15346 Exam):**

```c
main() {
   int number, index;
1. printf("Enter a number");
2. scanf("%d", &number);
3. index = 2;
4. while (index <= number - 1) {
6.   if (number % index == 0) {
8.     printf("Not a prime number");
9.     break;
10.  }
11.  index++;
12. }
13. if (index == number)
14.  printf("prime number");
15. } // end main
```

**Step 1: Identify Decision / Predicate Nodes ($P$)**
Looking at the code, decision branches occur at:
- Statement 4: `while (index <= number - 1)` (Loop condition)
- Statement 6: `if (number % index == 0)` (Divisibility test)
- Statement 13: `if (index == number)` (Prime check test)

Number of decision nodes: $P = 3$.

**Step 2: Calculate Cyclomatic Complexity**
Using the Predicate Node formula:
$$V(G) = P + 1 = 3 + 1 = 4$$

Using the Edges and Nodes formula ($E = 10 \text{ edges}, N = 8 \text{ nodes}$):
$$V(G) = E - N + 2 = 10 - 8 + 2 = 4$$

**Step 3: List the 4 Independent Basis Paths**
- **Path 1**: $1 \rightarrow 2 (\text{False}) \rightarrow 6 (\text{False}) \rightarrow 8$ (Loop does not execute, input $\le 2$).
- **Path 2**: $1 \rightarrow 2 (\text{False}) \rightarrow 6 (\text{True}) \rightarrow 7 \rightarrow 8$ (Direct prime test pass).
- **Path 3**: $1 \rightarrow 2 (\text{True}) \rightarrow 3 (\text{True}) \rightarrow 4 \rightarrow 6 \rightarrow 8$ (Divisor found, loop breaks with "Not a prime number").
- **Path 4**: $1 \rightarrow 2 (\text{True}) \rightarrow 3 (\text{False}) \rightarrow 5 \rightarrow 2 \dots \rightarrow 8$ (Divisor not found, increments `index`, loops again).

---

### 4.2 How to Calculate Defect Spoilage Step-by-Step

**Example Problem (QP 15346 Exam):**

| SDLC Phase | Number of Defects Found ($D$) | Defect Age ($A$) | Weighted Spoilage ($D \times A$) |
| :--- | :---: | :---: | :---: |
| **Requirement Specs** | 34 | 2 | $34 \times 2 = 68$ |
| **High Level Design (HLD)** | 25 | 3 | $25 \times 3 = 75$ |
| **Low Level Design (LLD)** | 17 | 7 | $17 \times 7 = 119$ |
| **Coding** | 10 | 8 | $10 \times 8 = 80$ |
| **TOTAL** | $\sum D = \mathbf{86}$ | — | $\sum (D \times A) = \mathbf{342}$ |

**Formula:**
$$\text{Defect Spoilage} = \frac{\sum (D \times A)}{\sum D}$$

**Calculation:**
$$\text{Defect Spoilage} = \frac{342}{86} \approx 3.9767 \quad (\approx 3.98)$$

**Interpretation to write in exam:**
A lower defect spoilage value is better. A value of $3.98$ indicates that defects are being discovered relatively late in the development lifecycle rather than in the phase where they originated, increasing the cost of fixing them.

---

### 4.3 Boundary Value Analysis (BVC) and Robust Test Case Design

**Problem:** A program reads 3 numbers $A, B, C$ in the range $[1, 100]$.

1. **Boundary Values for each variable:**
   - Minimum: $\min = 1$
   - Just above minimum: $\min+ = 2$
   - Nominal (Typical): $\text{nom} = 50$
   - Just below maximum: $\max- = 99$
   - Maximum: $\max = 100$
   - Out-of-bounds low (Robust): $\min- = 0$
   - Out-of-bounds high (Robust): $\max+ = 101$

2. **Total Test Cases Formula:**
   - Standard BVC: $4n + 1 = 4(3) + 1 = 13 \text{ Test Cases}$
   - Robust Testing: $6n + 1 = 6(3) + 1 = 19 \text{ Test Cases}$

---

### 4.4 McCall's Software Quality Model Made Simple

McCall's model organizes software quality into 3 Pillars with 11 Factors:

```text
1. Product Operation (How well does the software run day-to-day?)
   - Correctness: Does it satisfy specifications?
   - Reliability: Does it operate without failure?
   - Efficiency: Does it optimize CPU and memory use?
   - Integrity: Is unauthorized data access prevented?
   - Usability: Is it easy to learn and operate?

2. Product Revision (How easy is it to modify and fix?)
   - Maintainability: Can bugs be diagnosed and fixed easily?
   - Flexibility: Can new features be added easily?
   - Testability: Can the software be validated with ease?

3. Product Transition (How well does it adapt to new environments?)
   - Portability: Can it run on different hardware/OS?
   - Reusability: Can modules be reused in other projects?
   - Interoperability: Can it exchange data with other systems?
```

---

### 4.5 Bug Life Cycle State Machine Diagram

```text
[ New ] ---> [ Assigned ] ---> [ Open ] ---> [ Fixed ] ---> [ Pending Retest ] ---> [ Retest ] ---> [ Verified ] ---> [ Closed ]
                                  |                                                       |
                                  +--> [ Deferred ]                                       +--> (Failed) ---> [ Reopened ]
                                  +--> [ Rejected ]                                                                 |
                                  +--> [ Duplicate ]                                                                |
                                                                                                                    v
                                                                                                                [ Open ]
```

---

## 5. Section 4: 3-Hour Exam Strategy

```text
Time Block 1 (00:00 - 00:45) -> Q.4: Prime/Factorial DD-Graph, V(G) and Basis Paths (20 Marks)
Time Block 2 (00:45 - 01:30) -> Q.2 or Q.3: Defect Spoilage Calculation + BVC Tables (20 Marks)
Time Block 3 (01:30 - 02:15) -> Q.5/Q.6: McCall's Quality Model + Bug Lifecycle Diagram (20 Marks)
Time Block 4 (02:15 - 03:00) -> Q.1: Compulsory 5M (Testing Terminology, Six Sigma, Tools) (20 Marks)
```
