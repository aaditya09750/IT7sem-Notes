# Software Testing & Quality Assurance (STQA)
## Master Unified Question Bank & High-Yield Priority Guide
**Academic Context:** Mumbai University | B.E. / T.E. Information Technology | Semester VII (R-19 C-Scheme)  
**Subject Code:** 42676 (DLOC III)  
**Curated Sources:**
1. **MUSA (Mumbai University Students Association) Question Bank & Top 15 (Winter Session 2026)**
2. **MUSA STQA Complete Solutions Manual (`STQA MUSA Solutions.pdf` - 33 Pages)**
3. **Mumbai University Examination Paper Archive (QP Codes: 15346 & 28365)**

---

## Table of Contents
1. [Master Priority Matrix (Ranked by Recurrence & MUSA Weight)](#1-master-priority-matrix)
2. [Tier 1: Ultra High Frequency (100% Recurrence in Papers & MUSA Top-Tier)](#2-tier-1-ultra-high-frequency-100-recurrence)
3. [Tier 2: Very High Frequency (Core Syllabus & MUSA Top 15 Targets)](#3-tier-2-very-high-frequency-core-targets)
4. [Tier 3: High-Yield Specialized & Metric Questions](#4-tier-3-high-yield-specialized--metric-questions)
5. [MUSA Mandatory Section: Tabular Differentiations](#5-musa-mandatory-section-tabular-differentiations)
6. [MUSA Mandatory Section: High-Yield Short Notes](#6-musa-mandatory-section-high-yield-short-notes)
7. [Compulsory Numericals & Code DD-Graph Traces](#7-compulsory-numericals--code-dd-graph-traces)
8. [High-Scoring 80-Mark Exam Strategy](#8-high-scoring-80-mark-exam-strategy)

---

## 1. Master Priority Matrix

| Rank | Topic / Question Description | Exam Frequency | MUSA QB Ref | MUSA Top 15 Ref | Typical Marks | Priority Status |
| :---: | :--- | :---: | :---: | :---: | :---: | :--- |
| **01** | White-Box: DD-Graph, Cyclomatic Complexity $V(G)$ & Basis Paths | **100% of Papers** | Q.3 | **Top 15 #3** | 10M | `CRITICAL [Must Solve]` |
| **02** | Agile Testing Life Cycle (ATLC), Principles & Challenges | **100% of Papers** | Q.9 | **Top 15 #8** | 10M | `CRITICAL [Must Solve]` |
| **03** | Mutation Testing: Mutants, Kill Ratio & Mutation Score Formula | **100% of Papers** | Q.5 | **Top 15 #5** | 10M / 5M | `CRITICAL [Must Solve]` |
| **04** | Test Automation Tool Selection Criteria & Selenium WebDriver | **100% of Papers** | Q.15 | **Top 15 #12** | 10M / 5M | `CRITICAL [Must Solve]` |
| **05** | Structure of Testing Group & Test Management Elements | **100% of Papers** | Q.16 | **Top 15 #13** | 10M / 5M | `CRITICAL [Must Solve]` |
| **06** | Black-Box: Boundary Value Analysis (BVA) & Robustness Testing | **High Recurrence** | Q.2 | **Top 15 #2** | 10M | `VERY HIGH [Core Black-Box]`|
| **07** | Defect Spoilage Calculation & Metric Table Numerical | **High Recurrence** | Q.19 | **Top 15 #14** | 10M | `VERY HIGH [Guaranteed Num]`|
| **08** | McCall's Software Quality Factors & Quality Criteria Hierarchy | **High Recurrence** | Q.11 | **Top 15 #9** | 10M | `VERY HIGH [Core SQA]` |
| **09** | Defect / Bug Life Cycle: States, State-Transitions & Diagram | **High Recurrence** | Q.17 | **Top 15 #11** | 10M / 5M | `VERY HIGH [Bug Lifecycle]` |
| **10** | Testing Terminology: Error vs Fault vs Bug vs Failure | **High Recurrence** | Q.1 | **Top 15 #1** | 5M | `VERY HIGH [Compulsory Q.1]`|
| **11** | Integration Testing: Bottom-Up vs Top-Down (Stubs & Drivers) | **High Recurrence** | Q.6 | **Top 15 #6** | 10M / 5M | `VERY HIGH [Levels of Test]`|
| **12** | Web Application Testing: UI, Functional, Load & Security Issues | **High Recurrence** | Q.8 | **Top 15 #7** | 10M | `VERY HIGH [Specialized]` |
| **13** | Six Sigma Quality Principles & DMAIC Improvement Cycle | **High Recurrence** | Q.13 | **Top 15 #10** | 10M / 5M | `VERY HIGH [Quality Models]`|
| **14** | Test Suite Prioritization: Criteria, Coverage & Ordering Process| **Core Syllabus** | Q.18 | Master QB | 10M | `HIGH [Test Management]`|
| **15** | Structural Coverage Criteria: Statement, Branch, Condition | **Core Syllabus** | Q.4 | **Top 15 #4** | 10M / 5M | `HIGH [White-Box]` |
| **16** | CMM (Capability Maturity Model) 5 Levels vs TMM | **Core Syllabus** | Q.14 | Short Note (iii)| 10M | `HIGH [Process Standards]` |
| **17** | ISO 9000:2000 Series Quality Standards & Certification | **Core Syllabus** | Q.12 | Master QB | 10M / 5M | `HIGH [Standards]` |
| **18** | Bugzilla Defect Tracking System Workflow & Features | **Core Syllabus** | Short Note iv | Top 15 Q.16 Note | 5M | `HIGH [Tools/Lab]` |
| **19** | Loop Testing: Simple, Nested, Concatenated & Unstructured | **Core Syllabus** | Q.4 | **Top 15 #4** | 5M / 10M | `HIGH [White-Box]` |
| **20** | State Transition & State Table Testing | **Core Syllabus** | Q.7 | Master QB | 5M / 10M | `HIGH [Black-Box]` |

---

## 2. Tier 1: Ultra High Frequency (100% Recurrence)

### [STQA-01] White-Box Testing: DD-Graph, Cyclomatic Complexity & Basis Paths
- **Recurrence:** **100% of University Papers**
- **Exam Appearances:** QP 15346 (Q.4b - Prime Number Program), QP 28365 (Q.2a - Factorial Program & Q.4a - Graph Metrics)
- **MUSA Reference:** Question Bank **Q.3** and **Top 15 #3**
- **Typical Marks:** 10 Marks

#### Exact Question Formulation:
> "Consider following C program. Draw DD-graph, calculate cyclomatic complexity using all methods, list out independent paths and design test cases."

#### Examiner Expected Answers Checklist:
- **1. Decision-to-Decision (DD) Graph Construction:**
  - Nodes represent sequential sequences of statements ending in a decision.
  - Directed edges represent flow of control.
  - Every node and edge must be numbered.
- **2. Cyclomatic Complexity $V(G)$ Using All Three Methods (Mandatory):**
  - **Method 1 (Formula based on Edges & Nodes):**
    $$V(G) = E - N + 2P$$
    where $E = \text{number of edges}, N = \text{number of nodes}, P = \text{number of connected components} = 1$.
  - **Method 2 (Predicate Nodes):**
    $$V(G) = P + 1$$
    where $P = \text{number of decision / predicate nodes}$ (`if`, `while`, `for`).
  - **Method 3 (Enclosed Regions):**
    $$V(G) = R = \text{Total Enclosed Bounded Regions} + 1 \text{ (Unbounded Outer Region)}$$
- **3. Independent Basis Paths Enumeration:**
  - Must write out every basis path from Entry to Exit (e.g., $\text{Path 1}: 1 \to 2 \to 3 \to 7$, $\text{Path 2}: 1 \to 2 \to 4 \to 5 \to 6 \dots$).
- **4. Test Case Generation Table:**
  - Table columns: `Test Case ID`, `Input Data`, `Expected Output`, `Basis Path Exercised`.

---

### [STQA-02] Agile Testing Life Cycle (ATLC) & Challenges
- **Recurrence:** **100% of University Papers**
- **Exam Appearances:** QP 15346 (Q.2b), QP 28365 (Q.2b)
- **MUSA Reference:** Question Bank **Q.9** and **Top 15 #8**
- **Typical Marks:** 10 Marks

#### Examiner Expected Answers Checklist:
- **Definition:** Testing methodology adhering to Agile principles where testing is integrated continuously throughout the software development sprint, not treated as a separate post-coding phase.
- **Phases of Agile Testing Life Cycle (ATLC):**
  1. *Impact Assessment:* Analyzing user stories and sprint backlog requirements.
  2. *Agile Test Planning:* Formulating sprint test strategies, estimating test effort.
  3. *Release Readiness:* Continuous integration (CI), running automated test suites.
  4. *Daily Scrums & Retrospective:* Daily stand-up status updates and end-of-sprint lessons learned.
- **Agile Testing Quadrants (Draw 4-Quadrant Matrix):**
  - **Q1 (Unit/Component):** Technology-facing, supports team (Automated Unit tests, TDD).
  - **Q2 (Functional/Story):** Business-facing, supports team (Functional tests, Story acceptance, BDD).
  - **Q3 (Exploratory/Usability):** Business-facing, critiques product (Exploratory testing, User Acceptance).
  - **Q4 (Performance/Security):** Technology-facing, critiques product (Load, Stress, Pen testing).
- **Key Challenges:** Fast sprint velocity leaving little time for test automation, constantly mutating user requirements, regression testing overhead, lack of detailed specification documents.

---

### [STQA-03] Mutation Testing: Mutants, Kill Ratio & Mutation Score
- **Recurrence:** **100% of University Papers**
- **Exam Appearances:** QP 15346 (Q.5b), QP 28365 (Q.5b)
- **MUSA Reference:** Question Bank **Q.5** and **Top 15 #5**
- **Typical Marks:** 10 Marks / 5 Marks

#### Examiner Expected Answers Checklist:
- **Definition:** Fault-based white-box testing technique where deliberate syntactic errors (faults) are injected into the source code to create modified versions called **Mutants**.
- **Mutant Classification:**
  - *Killed Mutant:* Test suite produces different output for mutant than original code (test suite succeeded in catching the bug).
  - *Live / Survived Mutant:* Test suite fails to produce different output (test suite is inadequate).
  - *Equivalent Mutant:* Syntactically different but semantically identical to original program (can never be killed).
- **Mutation Operators:**
  - Replacing arithmetic operators ($+$ replaced by $-$).
  - Replacing relational operators ($<$ replaced by $\le$).
  - Variable replacement ($x$ replaced by $y$).
- **Mutation Score (Adequacy) Formula:**
  $$\text{Mutation Score (MS)} = \frac{K}{M - E} \times 100\%$$
  where $K = \text{number of killed mutants}, M = \text{total mutants generated}, E = \text{number of equivalent mutants}$.

---

### [STQA-04] Test Automation Tool Selection Criteria & Selenium WebDriver
- **Recurrence:** **100% of University Papers**
- **Exam Appearances:** QP 15346 (Q.3a), QP 28365 (Q.3a)
- **MUSA Reference:** Question Bank **Q.15** and **Top 15 #12**
- **Typical Marks:** 10 Marks / 5 Marks

#### Examiner Expected Answers Checklist:
- **Automation Tool Selection Criteria (Mandatory 8 Criteria):**
  1. *Platform & Technology Support:* Operating systems, browsers, programming languages supported.
  2. *Ease of Use & Learning Curve:* Scripting requirements vs codeless record/playback.
  3. *CI/CD Pipeline Integration:* Support for Jenkins, GitHub Actions, Docker.
  4. *Test Reporting & Analytics:* Detailed failure logs, screenshots, dashboards.
  5. *Maintenance Overhead:* Fragility of object locators (XPath/CSS) across UI changes.
  6. *Cost & Licensing:* Open source vs commercial tool pricing.
  7. *Data-Driven & Keyword-Driven Framework Support.*
  8. *Vendor & Community Support.*
- **Selenium WebDriver Architecture Diagram:**
  $$\text{Language Bindings (Java, Python)} \xrightarrow{\text{JSON Wire / W3C Protocol over HTTP}} \text{Browser Drivers (Chromedriver, Geckodriver)} \longrightarrow \text{Real Browsers (Chrome, Firefox)}$$

---

## 3. Tier 2: Very High Frequency (Core Targets)

### [STQA-05] Black-Box Testing: Boundary Value Analysis (BVA) & Robustness
- **MUSA Reference:** Question Bank **Q.2** and **Top 15 #2**
- **Typical Marks:** 10 Marks
- **Core Concept:** Software tends to fail at boundary conditions of input domains rather than in the center.
- **Value Selection for Input Domain $[a, b]$:**
  - Standard BVA ($4n + 1$ test cases): $a, a+1, \text{nominal}, b-1, b$.
  - Robustness Testing ($6n + 1$ test cases): Adds boundary excursions $a-1$ and $b+1$.
- **Equivalence Class Partitioning (ECP):** Divides input domain into valid equivalence classes and invalid equivalence classes. One representative value is chosen from each partition.

---

### [STQA-06] McCall's Software Quality Factors
- **MUSA Reference:** Question Bank **Q.11** and **Top 15 #9**
- **Typical Marks:** 10 Marks
- **3 Quality Perspectives (11 Factors - Draw McCall's Triangle):**
  1. **Product Operation:** Correctness, Reliability, Efficiency, Integrity, Usability.
  2. **Product Revision:** Maintainability, Flexibility, Testability.
  3. **Product Transition:** Portability, Reusability, Interoperability.

---

### [STQA-07] Defect / Bug Life Cycle (States, Transitions & Workflow)
- **MUSA Reference:** Question Bank **Q.17** and **Top 15 #11**
- **Typical Marks:** 10 Marks / 5 Marks
- **State Transition Flowchart:**
  $$\text{New} \longrightarrow \text{Assigned} \longrightarrow \text{Open} \longrightarrow \begin{cases} \text{Fixed} \longrightarrow \text{Pending Retest} \longrightarrow \text{Retest} \longrightarrow \text{Verified} \longrightarrow \text{Closed} \\ \text{Rejected} \\ \text{Duplicate} \\ \text{Deferred} \end{cases}$$
  *(If bug persists after Retest $\to$ Reopened).*

---

### [STQA-08] Integration Testing: Bottom-Up vs Top-Down (Stubs & Drivers)
- **MUSA Reference:** Question Bank **Q.6** and **Top 15 #6**
- **Typical Marks:** 10 Marks / 5 Marks
- **Top-Down Integration:** Integrates modules starting from main program down the hierarchy; requires **Stubs** (dummy subordinate modules simulating called functions).
- **Bottom-Up Integration:** Integrates atomic modules upward into clusters; requires **Drivers** (dummy control modules coordinating test inputs and receiving outputs).
- **Sandwich / Hybrid Integration:** Combines top-down and bottom-up approaches around a central target layer.

---

## 4. Tier 3: High-Yield Specialized & Metric Questions

1. **Defect Spoilage Calculation (MUSA QB Q.19 & Top 15 #14 - 10M):**
   - Quantitative metric calculating defect discovery latency across lifecycle phases; Defect Spoilage = $\frac{\sum (\text{Defects} \times \text{Discovery Penalty Weight})}{\text{Total Defects}}$.
2. **Six Sigma & DMAIC Methodology (MUSA QB Q.13 & Top 15 #10 - 10M/5M):**
   - Goal: $3.4$ Defects Per Million Opportunities (DPMO); DMAIC Phases: Define $\to$ Measure $\to$ Analyze $\to$ Improve $\to$ Control.
3. **Web Application Testing Challenges (MUSA QB Q.8 & Top 15 #7 - 10M):**
   - Cross-browser compatibility, responsive rendering on varying viewport sizes, stateless session timeouts, database race conditions, and vulnerability to XSS and CSRF.
4. **CMM (Capability Maturity Model) 5 Levels (MUSA QB Q.14 - 10M):**
   - Level 1 (Initial / Ad-hoc) $\to$ Level 2 (Repeatable / Managed) $\to$ Level 3 (Defined / Standardized) $\to$ Level 4 (Quantitatively Managed) $\to$ Level 5 (Optimizing / Continuous Improvement).

---

## 5. MUSA Mandatory Section: Tabular Differentiations

### 1. Software Quality Assurance (SQA) vs Software Quality Control (SQC)
| Parameter / Basis | Software Quality Assurance (SQA) | Software Quality Control (SQC) |
| :--- | :--- | :--- |
| **Focus** | Process-oriented (how software is built) | Product-oriented (inspecting the final build) |
| **Approach** | Proactive; prevents defects before they occur | Reactive; identifies defects after coding is done |
| **Activity** | Audits, training, process definitions, standards | Actual software execution, unit/system testing |
| **Responsibility** | Whole project team and management | Dedicated testing / QC team |

### 2. Verification vs Validation
| Parameter / Basis | Verification | Validation |
| :--- | :--- | :--- |
| **Guiding Question** | "Are we building the product right?" | "Are we building the right product?" |
| **Execution** | Static inspection (reviews, walkthroughs, inspections)| Dynamic testing (executing code with test data) |
| **Target** | Software architecture, design docs, code syntax | Final executable software against user requirements |
| **Timing** | Early phases of SDLC | Late phases of SDLC (System & Acceptance testing) |

### 3. White-Box Testing vs Black-Box Testing
| Parameter / Basis | White-Box (Structural) Testing | Black-Box (Functional) Testing |
| :--- | :--- | :--- |
| **Code Visibility** | Full internal source code logic is visible | Internal source code structure is hidden (opaque) |
| **Basis of Tests** | Control flow graphs, logic branches, code paths | Software specifications, user stories, requirements |
| **Performed By** | Software developers and specialized white-box testers | Independent testing team, end-users |
| **Techniques** | Statement, Branch, Condition coverage, Mutation | BVA, Equivalence Partitioning, Decision Tables |

### 4. Alpha Testing vs Beta Testing
| Parameter / Basis | Alpha Testing | Beta Testing |
| :--- | :--- | :--- |
| **Environment** | Controlled developer/testing laboratory | Real-world uncontrolled client/user environment |
| **Conducted By** | Internal employees and in-house QA engineers | Real external prospective customers / end-users |
| **Timing** | Conducted before software is released to the public | Conducted immediately prior to general commercial launch|
| **Feedback Goal** | Catch critical system crashes and major defects | Validate real-world usability and edge-case behavior|

### 5. Static Testing vs Dynamic Testing
| Parameter / Basis | Static Testing | Dynamic Testing |
| :--- | :--- | :--- |
| **Code Execution** | Code is NOT executed | Code MUST be executed on a computer processor |
| **Techniques** | Desk checking, code walkthroughs, formal inspections | Unit, integration, system, regression testing |
| **Cost of Fix** | Extremely cheap; catches errors during design/coding | Expensive; catches bugs in compiled builds |
| **Finds What?** | Undeclared variables, dead code, logic inconsistencies | Memory leaks, functional failures, performance bottlenecks |

---

## 6. MUSA Mandatory Section: High-Yield Short Notes

1. **Pesticide Paradox & Testing Principles (MUSA Short Note i):**
   - *Pesticide Paradox:* Running the same set of test cases repeatedly causes them to lose effectiveness at finding new bugs, just like insects build immunity to pesticides. Test suites must be continually revised.
   - *Testing Shows Presence of Defects:* Testing can prove defects exist, but can never prove zero defects remain.
2. **Selenium WebDriver Architecture (MUSA Short Note ii):**
   - Directly controls browser via browser-native API; replaces deprecated JavaScript-injected Selenium RC; conforms to W3C WebDriver specification.
3. **Test Maturity Model - TMM (MUSA Short Note iii):**
   - 5-level framework complementary to CMM evaluating testing process maturity: Level 1 (Initial), Level 2 (Phase Definition), Level 3 (Integration), Level 4 (Management & Measurement), Level 5 (Optimization/Defect Prevention).
4. **Bugzilla Workflow (MUSA Short Note iv):**
   - Open-source defect tracking tool; captures bug summary, severity (Blocker, Critical, Normal), priority (P1–P5), hardware/OS environment, and tracks status transitions from NEW to CLOSED.
5. **Defect Density (MUSA Short Note v):**
   - Metric measuring software quality relative to size: $\text{Defect Density} = \frac{\text{Total Defects Found}}{\text{Size (KLOC or Function Points)}}$.

---

## 7. Compulsory Numericals & Code DD-Graph Traces

### Cyclomatic Complexity & Independent Paths Trace (10-Mark Blueprint)
**Sample Code:**
```c
1: int check_prime(int n) {
2:     int i = 2;
3:     if (n <= 1)
4:         return 0;
5:     while (i * i <= n) {
6:         if (n % i == 0)
7:             return 0;
8:         i++;
9:     }
10:    return 1;
11: }
```

**Step-by-Step Solution:**
1. **Identify Decision Nodes ($P$):**
   - Line 3: `if (n <= 1)` $\to$ Decision 1
   - Line 5: `while (i * i <= n)` $\to$ Decision 2
   - Line 6: `if (n % i == 0)` $\to$ Decision 3
   - Total Predicate Nodes $P = 3$.
2. **Calculate Cyclomatic Complexity:**
   $$V(G) = P + 1 = 3 + 1 = \mathbf{4}$$
3. **Enumerate 4 Basis Paths:**
   - $\text{Path 1}: 1 \to 2 \to 3 \to 4 \text{ (Exit)}$ [$n \le 1$]
   - $\text{Path 2}: 1 \to 2 \to 3 \to 5 \to 10 \text{ (Exit)}$ [while loop condition false immediately]
   - $\text{Path 3}: 1 \to 2 \to 3 \to 5 \to 6 \to 7 \text{ (Exit)}$ [divisible by $i$]
   - $\text{Path 4}: 1 \to 2 \to 3 \to 5 \to 6 \to 8 \to 5 \dots \to 10 \text{ (Exit)}$ [iterates while loop without dividing, returns 1]
4. **Design Test Cases:**
   - Test Case 1: $n = 0 \implies \text{Output } 0$ (Exercises Path 1).
   - Test Case 2: $n = 2 \implies \text{Output } 1$ (Exercises Path 2).
   - Test Case 3: $n = 4 \implies \text{Output } 0$ (Exercises Path 3).
   - Test Case 4: $n = 7 \implies \text{Output } 1$ (Exercises Path 4).

---

## 8. High-Scoring 80-Mark Exam Strategy

1. **Solve DD-Graph & Cyclomatic Complexity First:**
   - White-box DD-Graph questions are 100% mathematical and objective. Drawing the graph and stating the 3 complexity methods guarantees an immediate 10/10 marks.
2. **Memorize the Mutation Testing & Spoilage Formulas:**
   - Stating $\text{MS} = \frac{K}{M - E} \times 100\%$ and explaining Equivalent Mutants elevates your technical credibility.
3. **Dominate Question 1 (20 Marks Compulsory):**
   - The 5 MUSA comparisons (SQA vs SQC, Verification vs Validation, White-Box vs Black-Box, Alpha vs Beta, Static vs Dynamic) frequently comprise 15 out of 20 marks in Question 1.
