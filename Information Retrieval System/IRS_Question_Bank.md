# Information Retrieval System (IRS)
## Semester VII - Mumbai University (R-19 C-Scheme) | Subject Code: 42680 (DLOC - IV)

---

## Table of Contents
- [1. Question Frequency and Priority Overview](#1-question-frequency-and-priority-overview)
- [2. Section 1: 5-Mark Questions (Ranked by Frequency)](#2-section-1-5-mark-questions-ranked-by-frequency)
  - [2.1 Repeated 4 Times (Highest Priority)](#21-repeated-4-times-highest-priority)
  - [2.2 Repeated 3 Times](#22-repeated-3-times)
  - [2.3 Repeated 2 Times](#23-repeated-2-times)
  - [2.4 Single Appearance Questions](#24-single-appearance-questions)
- [3. Section 2: 10-Mark Questions (Ranked by Frequency)](#3-section-2-10-mark-questions-ranked-by-frequency)
  - [3.1 Repeated 4 Times (Must Solve)](#31-repeated-4-times-must-solve)
  - [3.2 Repeated 3 Times](#32-repeated-3-times)
  - [3.3 Repeated 2 Times](#33-repeated-2-times)
  - [3.4 Single Appearance Questions](#34-single-appearance-questions)
- [4. Section 3: Step-by-Step Solved Numericals and Algorithmic Blueprints](#4-section-3-step-by-step-solved-numericals-and-algorithmic-blueprints)
  - [4.1 How to Solve Vector Space TF-IDF Cosine Ranking Problems](#41-how-to-solve-vector-space-tf-idf-cosine-ranking-problems)
  - [4.2 How to Build a Boyer-Moore Bad Match Shift Table](#42-how-to-build-a-boyer-moore-bad-match-shift-table)
  - [4.3 How to Construct an Inverted Index with Block Addressing](#43-how-to-construct-an-inverted-index-with-block-addressing)
  - [4.4 Understanding the Rocchio Relevance Feedback Formula](#44-understanding-the-rocchio-relevance-feedback-formula)
- [5. Section 4: 3-Hour Exam Strategy](#5-section-4-3-hour-exam-strategy)

---

## 1. Question Frequency and Priority Overview

This overview ranks every topic by how often it appeared in the last 5 exam papers (2023 to 2025).

| Rank | Topic / Question | Typical Marks | Appearances | Recurrence Rate | Priority Level |
| :---: | :--- | :---: | :---: | :---: | :--- |
| 1 | Inverted Index Creation & Block Addressing Optimization | 10M | 4 / 5 Papers | 80% | Must Prepare First |
| 2 | User Relevance Feedback (Rocchio Formula & Search Models) | 5M / 10M | 4 / 5 Papers | 80% | Must Prepare First |
| 3 | Keyword-Based Queries (Phrase, Proximity, Wildcard) | 5M / 10M | 4 / 5 Papers | 80% | Must Prepare First |
| 4 | Natural Language Modelling Issues and Solutions in IR | 5M / 10M | 4 / 5 Papers | 80% | Must Prepare First |
| 5 | Multimedia IR (Video VIR and Image IIR Techniques) | 5M / 10M | 4 / 5 Papers | 80% | Must Prepare First |
| 6 | HCI Design Principles & Information Access Visualization | 5M / 10M | 4 / 5 Papers | 80% | Must Prepare First |
| 7 | Objectives of IR and Retrieval Process Pipeline Diagram | 5M | 4 / 5 Papers | 80% | Must Prepare First |
| 8 | Vector Space Model TF-IDF Cosine Document Ranking | 10M | 3 / 5 Papers | 60% | Must Prepare First |
| 9 | Search Engine Architecture and Crawling/Indexing Steps | 5M | 3 / 5 Papers | 60% | High Priority |
| 10 | Suffix Structures (Suffix Trie, Suffix Tree, Suffix Array) | 10M | 2 / 5 Papers | 40% | High Priority |
| 11 | Text Preprocessing Phases (Tokenization, Stemming) | 10M | 2 / 5 Papers | 40% | High Priority |
| 12 | Automatic Local Analysis for Query Expansion | 10M | 2 / 5 Papers | 40% | Medium Priority |
| 13 | Query Specification (Direct Manipulation vs Boolean) | 10M | 2 / 5 Papers | 40% | Medium Priority |
| 14 | Information Retrieval (IR) vs Data Retrieval (DR) | 5M | 2 / 5 Papers | 40% | Medium Priority |
| 15 | Text Compression (Huffman Algorithm and Dictionary) | 5M / 10M | 2 / 5 Papers | 40% | Medium Priority |

---

## 2. Section 1: 5-Mark Questions (Ranked by Frequency)

### 2.1 Repeated 4 Times (Highest Priority)

#### Question 5M-01: Objectives of Information Retrieval and the Retrieval Process
- **Exam Appearances**: 10/06/2025 (Q.1a), NOV 2025 (Q.1d), 14/12/2024 (Q.1a), JUNE 2024 (Q.1a)
- **Verbatim Questions**:
  1. *10/06/2025 (Q.1a)*: "Recall objectives of Information Retrieval Process (05)"
  2. *NOV 2025 (Q.1d)*: "Explain the Retrieval Process with neat labelled diagram (05)"
  3. *14/12/2024 (Q.1a)*: "Discuss Objective of IRS. (05)"
  4. *JUNE 2024 (Q.1a)*: "Discuss Objective of IRS (05)"

**Simple Concept Summary for Students:**
- **Objectives of IRS**: Help users find relevant information from large collections of unstructured text, minimize search time, provide high precision (avoid irrelevant clutter), and high recall (don't miss relevant documents).
- **Retrieval Process Steps to Draw**:
  1. Collection of Documents -> Text Operations (Tokenization, Stop-word removal, Stemming) -> Indexing -> Inverted Index Database.
  2. User Information Need -> Query Formulation -> Matching & Ranking Engine -> Ranked Document Output -> User Relevance Feedback loop.

---

### 2.2 Repeated 3 Times

#### Question 5M-02: Search Engine Architecture, Tasks, and Operation Steps
- **Exam Appearances**: 10/06/2025 (Q.1c), JUNE 2024 (Q.1d), 22/06/2023 (Q.1.4)
- **Verbatim Question**: "Identify various tasks performed by web search engine. List steps of search operation. Explain search engine Architecture. (05)"

**3 Main Components of a Search Engine:**
1. **Web Crawler (Spider)**: Traverses the internet following hyperlinks to download web pages.
2. **Indexer**: Parses downloaded pages, extracts text terms, and creates an Inverted Index.
3. **Query Engine (Ranking Processor)**: Evaluates user query terms against the index, computes similarity scores (like PageRank + TF-IDF), and presents ranked URLs.

---

### 2.3 Repeated 2 Times

| Question Topic | Exam Sessions | What to Write in the Answer |
| :--- | :--- | :--- |
| **Information Retrieval (IR) vs Data Retrieval (DR)** | 10/06/2025 (Q.1b), NOV 2025 (Q.1a) | **DR** operates on structured relational tables (SQL) where matching is exact (Deterministic), returning 100% matching rows. **IR** operates on unstructured natural text where matching is partial and probabilistic, returning ranked relevant documents. |
| **Markup Languages (XML, SGML, HTML)** | 10/06/2025 (Q.6b), 14/12/2024 (Q.1b) | Explain semi-structured text representation. HTML is for display formatting, XML is for structured data exchange with user-defined tags, SGML is the generalized meta-language standard. |
| **Interface Support for Search & Starting Points** | 14/12/2024 (Q.6d), JUNE 2024 (Q.6c) | Search UI support features: Auto-completion, query spell check ("Did you mean?"), faceted filtering, search history, and visual topic overviews. |
| **Text Compression (Statistical vs Dictionary)** | 14/12/2024 (Q.4a), 22/06/2023 (Q.6.4) | Statistical methods (Huffman coding) assign shorter bitcodes to frequently occurring letters. Dictionary methods (LZW, LZ77) replace recurring word strings with integer token pointers. |

---

### 2.4 Single Appearance Questions

- **Metadata and its Types** (10/06/2025 Q.1d): Descriptive metadata (author, title), Structural metadata (page order, chapters), Administrative metadata (access rights, creation date).
- **Types of Information Systems** (10/06/2025 Q.6a): DBMS (structured records), IRS (text retrieval), Decision Support Systems (DSS), Expert Systems.
- **Meta Searchers and Merits** (NOV 2025 Q.1b): Dispatches one user query across multiple external search engines simultaneously, combines results, removes duplicates, and provides wider web coverage.
- **Mobile UX Visualization (Case Study)** (NOV 2025 Q.1c): Design charts (pie/donut charts for category spending, line graphs for monthly trends) for intuitive mobile banking display.
- **Structured Text Retrieval Models** (14/12/2024 Q.1c): Models that allow querying both text content and document structure simultaneously (e.g., searching for "author = John" inside `<chapter>` tags).
- **Keyword Queries Illustration** (14/12/2024 Q.1d): Single-term queries, multi-term Boolean queries (`AND`, `OR`, `NOT`), and Phrase queries (`"machine learning"`).
- **Digital Libraries** (14/12/2024 Q.6b): Digital document preservation, Dublin Core metadata standards, catalog search.
- **Data Modeling** (JUNE 2024 Q.1b): Conceptual data modeling and schema structuring in text retrieval systems.
- **Proximity Queries vs Wildcard Queries** (JUNE 2024 Q.1c): Proximity queries find terms within $k$ words of each other (`"cloud" NEAR/3 "security"`). Wildcard queries find patterns with missing characters (`comput*` matches computer, computing, computation).
- **Sequential Search** (JUNE 2024 Q.6a): Linear byte-by-byte scanning (grep) of text when no pre-built index exists.
- **Document Clustering** (JUNE 2024 Q.6b): Grouping documents based on shared vocabulary similarity without predefined labels.
- **Classic IR Models** (22/06/2023 Q.1.1): Boolean Model (exact set match), Vector Space Model (geometric angle), Probabilistic Model (probability of relevance).
- **Natural Language in IR** (22/06/2023 Q.1.2): Syntax, semantics, and handling lexical ambiguity.
- **Quality of Information Parameters** (22/06/2023 Q.1.3): Accuracy, timeliness, completeness, credibility, relevance.
- **Lexical Analysis** (22/06/2023 Q.6.1): Tokenizing character streams, stripping punctuation, converting to lowercase.
- **Web IR and Link Analysis** (22/06/2023 Q.6.2): PageRank, inbound link authority, anchor text indexing.
- **Automatic Feature Extraction** (22/06/2023 Q.6.3): Calculating TF-IDF term weights automatically from document text.

---

## 3. Section 2: 10-Mark Questions (Ranked by Frequency)

---

### 3.1 Repeated 4 Times (Must Solve)

#### Question 10M-01: Inverted Index Creation and Block Addressing Optimization
- **Exam Appearances**: NOV 2025 (Q.4a), 14/12/2024 (Q.4b), JUNE 2024 (Q.5b), 22/06/2023 (Q.5.1)
- **Verbatim Question**: "Describe the process of creating an inverted index with an example. How can this process be optimized using block addressing? / What is inverted Index? Create inverted index without stop words for: 'This is a text. A text has many words. Words are made from letters.' (10)"

**Key Concepts to Write in Exam:**
- **What is an Inverted Index?** A mapping from terms/words to the list of documents (and exact word positions) where they occur.
- **Components**: Vocabulary / Lexicon (unique terms) + Postings List (Document IDs and frequencies).
- **Block Addressing Optimization**: Instead of storing exact document pointers or byte offsets, the collection is split into fixed-size blocks (e.g., 64 KB). The index points to Block IDs, reducing pointer memory overhead by 70% to 80%.

#### Question 10M-02: User Relevance Feedback (Rocchio Formula & Search Models)
- **Exam Appearances**: NOV 2025 (Q.6a), 14/12/2024 (Q.6a), JUNE 2024 (Q.2a), 22/06/2023 (Q.2.1)
- **Verbatim Question**: "Explain how user relevance feedback model can be applied to improve search results in a search recommendation engine. Explain Rocchio relevance feedback formula. (10)"

---

### 3.2 Repeated 3 Times

#### Question 10M-03: Keyword-Based Queries (Phrase, Proximity, Wildcard)
- **Exam Appearances**: 10/06/2025 (Q.4a), NOV 2025 (Q.3a), JUNE 2024 (Q.4a)
- **Verbatim Question**: "What is the purpose of using keyword-based query? Briefly explain any 3 types of keyword-based queries with examples. (10)"

#### Question 10M-04: Natural Language Modelling Issues & Solutions in IR
- **Exam Appearances**: 10/06/2025 (Q.3b), NOV 2025 (Q.6b), 14/12/2024 (Q.2b)
- **Verbatim Question**: "Explain Natural language modelling issues and its solution in IR. Summarize different issues for modelling natural language. (10)"

**4 Core Issues and Their IR Solutions:**
1. **Polysemy** (One word has multiple meanings, e.g., "bank" = river bank or financial bank) -> Solved using Word Sense Disambiguation and Contextual Word Embeddings.
2. **Synonymy** (Different words have the same meaning, e.g., "buy" and "purchase") -> Solved using Query Expansion with Thesauri / WordNet.
3. **Morphological Variations** (run, running, ran) -> Solved using Stemming (Porter Stemmer) or Lemmatization.
4. **Structural Ambiguity** -> Solved using POS Tagging and Dependency Parsing.

#### Question 10M-05: Multimedia Information Retrieval (VIR & IIR)
- **Exam Appearances**: NOV 2025 (Q.5a), 14/12/2024 (Q.3b), 22/06/2023 (Q.3.1)
- **Verbatim Question**: "Explain Video Information Retrieval (VIR) and Image Information Retrieval (IIR). Describe 3 techniques in VIR and 3 in IIR. Discuss how these improve user experience. (10)"

**Key Techniques to List:**
- **Image IR (IIR)**: Color Histograms, Texture Extraction (Gabor filters), Shape Boundaries, Deep CNN Feature Embeddings.
- **Video IR (VIR)**: Shot Boundary Detection (Keyframe extraction), Motion Vector Analysis, Audio Subtitle Alignment.

#### Question 10M-06: Vector Space Model TF-IDF Cosine Document Ranking
- **Exam Appearances**: 10/06/2025 (Q.2b), NOV 2025 (Q.2b), 14/12/2024 (Q.2a)
- **Verbatim Question**: "Consider small collection C consisting of documents d1, d2, d3. Given query q, calculate the rank of each document using vector space retrieval model and cosine similarity measure. (10)"

#### Question 10M-07: Human-Computer Interaction (HCI) Principles & Visualization
- **Exam Appearances**: 10/06/2025 (Q.5a), JUNE 2024 (Q.3b & Q.5a), 22/06/2023 (Q.3.2)
- **Verbatim Question**: "What is human-computer interaction? Discuss four design principles for information access interfaces. Summarize visualization techniques. (10)"

---

### 3.3 Repeated 2 Times

- **Suffix Data Structures (Suffix Trie, Tree, Array & Supra Index)** (10/06/2025 Q.5b, 14/12/2024 Q.3a)
- **Text Preprocessing Phases within Documents** (14/12/2024 Q.5a, JUNE 2024 Q.2b)
- **Automatic Local Analysis for Query Expansion** (JUNE 2024 Q.3a, 22/06/2023 Q.2.2)
- **Query Specification (Direct Manipulation vs Boolean)** (NOV 2025 Q.4b, 22/06/2023 Q.5.2)

---

### 3.4 Single Appearance Questions

- **Taxonomy of IR Models & Browsing Models** (10/06/2025 Q.2a - 10M)
- **Boolean Retrieval Model Detailed** (10/06/2025 Q.3a - 10M)
- **Boyer-Moore Algorithm & Bad Match Table Construction** (10/06/2025 Q.4b - 10M)
- **Structured Text Retrieval Models** (NOV 2025 Q.2a - 10M)
- **Meta Search Engine Architecture** (NOV 2025 Q.3b - 10M)
- **Java Collection Framework Case Study in Student Search** (NOV 2025 Q.5b - 10M)
- **Importance of Context in IR** (NOV 2025 Q.6c - 10M)
- **Huffman Compression Algorithm in Detail** (14/12/2024 Q.4a - 10M)
- **Probabilistic Retrieval Model (Inference Networks)** (14/12/2024 Q.5b - 10M)
- **Starting Point: Collections and Overviews** (JUNE 2024 Q.4b - 10M)
- **Object Oriented and Object Relational DBMS** (22/06/2023 Q.4.1 - 10M)
- **Scalar and Metrics Clusters** (22/06/2023 Q.4.2 - 10M)

---

## 4. Section 3: Step-by-Step Solved Numericals and Algorithmic Blueprints

### 4.1 How to Solve Vector Space TF-IDF Cosine Ranking Problems

**Example Problem (10/06/2025 Exam):**
- Collection $C$ with $N = 3$ documents:
  - $d_1$: `"beautiful garden"`
  - $d_2$: `"evening garden time"`
  - $d_3$: `"garden time is beautiful"`
- Query $q$: `"garden time"`

**Step 1: Determine Vocabulary and Term Frequencies (TF)**
Count how many times each term appears in each document:

| Term ($t$) | $d_1$ (TF) | $d_2$ (TF) | $d_3$ (TF) | $q$ (TF) | Document Frequency ($df_t$) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **beautiful** | 1 | 0 | 1 | 0 | 2 |
| **evening** | 0 | 1 | 0 | 0 | 1 |
| **garden** | 1 | 1 | 1 | 1 | 3 |
| **is** | 0 | 0 | 1 | 0 | 1 |
| **time** | 0 | 1 | 1 | 1 | 2 |

**Step 2: Compute Inverse Document Frequency (IDF)**
Formula: $\text{IDF}_t = \log_{10}\left(\frac{N}{df_t}\right)$ with $N = 3$:
- $\text{IDF}(\text{beautiful}) = \log_{10}(3/2) = \log_{10}(1.5) = 0.176$
- $\text{IDF}(\text{evening}) = \log_{10}(3/1) = \log_{10}(3.0) = 0.477$
- $\text{IDF}(\text{garden}) = \log_{10}(3/3) = \log_{10}(1.0) = 0.000$ (appears in all documents)
- $\text{IDF}(\text{is}) = \log_{10}(3/1) = \log_{10}(3.0) = 0.477$
- $\text{IDF}(\text{time}) = \log_{10}(3/2) = \log_{10}(1.5) = 0.176$

**Step 3: Compute TF-IDF Weights ($w_{t,d} = \text{TF} \times \text{IDF}$)**
- For Query $q$:
  - $w(\text{garden}, q) = 1 \times 0.000 = 0.000$
  - $w(\text{time}, q) = 1 \times 0.176 = 0.176$
  - Query vector: $q = [0, 0, 0, 0, 0.176]$ (magnitude $\|q\| = 0.176$)
- For $d_1$: $w(\text{beautiful}) = 0.176$, $w(\text{garden}) = 0.000$, $w(\text{time}) = 0$
  - Dot product $q \cdot d_1 = 0 \implies \text{Score}(q, d_1) = \mathbf{0.00}$
- For $d_2$: $w(\text{evening}) = 0.477$, $w(\text{garden}) = 0.000$, $w(\text{time}) = 0.176$
  - Magnitude $\|d_2\| = \sqrt{0.477^2 + 0.176^2} = \sqrt{0.2275 + 0.0310} = \sqrt{0.2585} = 0.508$
  - Dot product $q \cdot d_2 = 0.176 \times 0.176 = 0.0310$
  - $\text{Score}(q, d_2) = \frac{0.0310}{0.176 \times 0.508} = \frac{0.0310}{0.0894} = \mathbf{0.3467}$
- For $d_3$: $w(\text{beautiful}) = 0.176$, $w(\text{is}) = 0.477$, $w(\text{time}) = 0.176$
  - Magnitude $\|d_3\| = \sqrt{0.176^2 + 0.477^2 + 0.176^2} = \sqrt{0.0310 + 0.2275 + 0.0310} = \sqrt{0.2895} = 0.538$
  - Dot product $q \cdot d_3 = 0.176 \times 0.176 = 0.0310$
  - $\text{Score}(q, d_3) = \frac{0.0310}{0.176 \times 0.538} = \frac{0.0310}{0.0947} = \mathbf{0.3273}$

**Final Ranked Output:**
1. **Rank 1**: Document $d_2$ (Score: $0.3467$)
2. **Rank 2**: Document $d_3$ (Score: $0.3273$)
3. **Rank 3**: Document $d_1$ (Score: $0.0000$)

---

### 4.2 How to Build a Boyer-Moore Bad Match Shift Table

**Rule for Bad Character Shift:**
For a pattern $P$ of length $m$:
$$\text{Shift}(c) = \max(1, m - 1 - \text{last index of } c \text{ in } P)$$
If character $c$ is not in the pattern, $\text{Shift} = m$.

**Example Pattern: `"SMART"` ($m = 5$)**

| Character in Pattern | 0-Indexed Position | Calculation | Shift Value |
| :---: | :---: | :---: | :---: |
| **S** | 0 | $5 - 1 - 0$ | **4** |
| **M** | 1 | $5 - 1 - 1$ | **3** |
| **A** | 2 | $5 - 1 - 2$ | **2** |
| **R** | 3 | $5 - 1 - 3$ | **1** |
| **T** | 4 | Last letter | **5** (or $m$) |
| **Any other letter ($\ast$)** | Not present | Default length $m$ | **5** |

---

### 4.3 How to Construct an Inverted Index with Block Addressing

**Sample Text:**
- $d_1$: `"text text words"`
- $d_2$: `"words made letters"`

**Inverted Postings List:**
```text
letters -> [d2: position 3]
made    -> [d2: position 2]
text    -> [d1: positions 1, 2]
words   -> [d1: position 3] -> [d2: position 1]
```

**Block Addressing Optimization:**
Instead of storing 64-bit document memory pointers, documents are grouped into 64 KB storage blocks:
```text
letters -> [Block 1]
made    -> [Block 1]
text    -> [Block 1]
words   -> [Block 1]
```

---

### 4.4 Understanding the Rocchio Relevance Feedback Formula

$$q_m = \alpha \, q_0 + \beta \left( \frac{1}{|D_r|} \sum_{d_j \in D_r} d_j \right) - \gamma \left( \frac{1}{|D_{nr}|} \sum_{d_k \in D_{nr}} d_k \right)$$

- $q_0$: The original query typed by the user.
- $D_r$: The set of documents marked as **Relevant** by the user.
- $D_{nr}$: The set of documents marked as **Non-Relevant** by the user.
- $\alpha, \beta, \gamma$: Weight multipliers (Standard: $\alpha=1.0$, $\beta=0.75$, $\gamma=0.15$). The modified query $q_m$ moves closer to the cluster of relevant documents and away from irrelevant documents.

---

## 5. Section 4: 3-Hour Exam Strategy

```text
Time Block 1 (00:00 - 00:45) -> Q.2: Vector Space TF-IDF Cosine Ranking Numerical (20 Marks)
Time Block 2 (00:45 - 01:30) -> Q.4 or Q.5: Inverted Index + Suffix Tree / Boyer-Moore (20 Marks)
Time Block 3 (01:30 - 02:15) -> Q.3/Q.6: Multimedia IR (VIR/IIR) + Rocchio RF (20 Marks)
Time Block 4 (02:15 - 03:00) -> Q.1: Compulsory 5M (IR vs DR, Search Engine Arch) (20 Marks)
```
