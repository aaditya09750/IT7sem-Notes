# Artificial Intelligence and Data Science - II (AI and DS II)
## Semester VII - Mumbai University (R-19 C-Scheme) | Subject Code: 42671

---

## Table of Contents
- [1. Question Frequency and Priority Overview](#1-question-frequency-and-priority-overview)
- [2. Section 1: 5-Mark Questions (Ranked by Frequency)](#2-section-1-5-mark-questions-ranked-by-frequency)
  - [2.1 Repeated 5 Times (Highest Priority)](#21-repeated-5-times-highest-priority)
  - [2.2 Repeated 3 Times](#22-repeated-3-times)
  - [2.3 Repeated 2 Times](#23-repeated-2-times)
  - [2.4 Single Appearance Questions](#24-single-appearance-questions)
- [3. Section 2: 10-Mark Questions (Ranked by Frequency)](#3-section-2-10-mark-questions-ranked-by-frequency)
  - [3.1 Repeated 6 Times (100% Recurrence in All Papers)](#31-repeated-6-times-100-recurrence-in-all-papers)
  - [3.2 Repeated 5 Times](#32-repeated-5-times)
  - [3.3 Repeated 4 Times](#33-repeated-4-times)
  - [3.4 Repeated 3 Times](#34-repeated-3-times)
  - [3.5 Repeated 2 Times](#35-repeated-2-times)
  - [3.6 Single Appearance Questions](#36-single-appearance-questions)
- [4. Section 3: Step-by-Step Solved Numericals and Blueprints](#4-section-3-step-by-step-solved-numericals-and-blueprints)
  - [4.1 How to Solve Confusion Matrix Numericals](#41-how-to-solve-confusion-matrix-numericals)
  - [4.2 How to Solve Bayes Theorem Medical Probability Problems](#42-how-to-solve-bayes-theorem-medical-probability-problems)
  - [4.3 How to Design a Mamdani Fuzzy Washing Machine Controller](#43-how-to-design-a-mamdani-fuzzy-washing-machine-controller)
- [5. Section 4: 3-Hour Exam Strategy](#5-section-4-3-hour-exam-strategy)

---

## 1. Question Frequency and Priority Overview

This overview ranks every topic by how often it appeared in the last 6 exam papers (2023 to 2025). Focus your study time on the highest frequency topics first.

| Rank | Topic / Question | Typical Marks | Appearances | Recurrence Rate | Priority Level |
| :---: | :--- | :---: | :---: | :---: | :--- |
| 1 | Classifier Evaluation Metrics & Confusion Matrix Numericals | 10M | 6 / 6 Papers | 100% | Must Prepare First |
| 2 | Convolutional Neural Network (CNN) Architecture | 10M | 5 / 6 Papers | 83% | Must Prepare First |
| 3 | Multimodal Data Science (Text, Audio, Image, Video) | 10M | 5 / 6 Papers | 83% | Must Prepare First |
| 4 | Bayes' Theorem (Concept & Step-by-Step Numericals) | 5M | 5 / 6 Papers | 83% | Must Prepare First |
| 5 | Mamdani Fuzzy Controller Design (Washing Machine) | 10M | 4 / 6 Papers | 67% | High Priority |
| 6 | Ensemble Methods (Bagging, Boosting, Random Forest) | 10M | 4 / 6 Papers | 67% | High Priority |
| 7 | Cognitive Systems (Design Principles & Architecture) | 10M | 4 / 6 Papers | 67% | High Priority |
| 8 | McCulloch-Pitts Neuron Model (AND / XOR Logic) | 5M / 10M | 4 / 6 Papers | 67% | High Priority |
| 9 | Defuzzification Methods (Centroid / Center of Gravity) | 5M / 10M | 4 / 6 Papers | 67% | High Priority |
| 10 | Knowledge Representation: Taxonomies and Ontologies | 10M | 3 / 6 Papers | 50% | Medium Priority |
| 11 | Bayesian Belief Networks (BBN) and Conditional Tables | 10M | 3 / 6 Papers | 50% | Medium Priority |
| 12 | Markov Decision Process (MDP) and Bellman Equation | 5M / 10M | 3 / 6 Papers | 50% | Medium Priority |
| 13 | Long Short-Term Memory (LSTM) Internal Gating | 5M / 10M | 3 / 6 Papers | 50% | Medium Priority |
| 14 | Autoencoders for Dimensionality Reduction | 10M | 2 / 6 Papers | 33% | Medium Priority |
| 15 | Crisp Sets vs Fuzzy Sets and Membership Functions | 10M | 2 / 6 Papers | 33% | Medium Priority |

---

## 2. Section 1: 5-Mark Questions (Ranked by Frequency)

### 2.1 Repeated 5 Times (Highest Priority)

#### Question 5M-01: Bayes' Theorem (Theory and Practical Numericals)
- **Exam Appearances**: Dec 2025 (Q.1c & Q.1f), Nov 2024 (Q.1a), May 2024 (Q.1a), Dec 2023 (Q.1a), Jun 2023 (Q.6e)
- **Verbatim Questions**:
  1. *Dec 2025 (Q.1c)*: "How does Bayes Theorem determines the probability of an event with uncertain knowledge? Give one example of it. (05)"
  2. *Dec 2025 (Q.1f)*: "A medical test for a disease is 99% accurate. The disease is rare and affects 1 in 10,000 people. Use Bayes' Theorem to calculate the probability that a person who tests positive actually has the disease. (05)"
  3. *Nov 2024 (Q.1a)*: "Explain Bayes theorem. (05)"
  4. *May 2024 (Q.1a)*: "From a standard deck of playing cards, a single card is drawn. The probability that the card is king is 4/52, then calculate posterior probability P(King|Face). (05)"
  5. *Dec 2023 (Q.1a)*: "From below given probability distribution find P (~ Cavity | Toothache). (05)"

**Simple Concept Summary for Students:**
- **What is Bayes' Theorem?** It is a mathematical rule to update our initial belief (prior probability) about an event after observing new evidence.
- **Formula**:
  $$P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}$$
- **Term Meanings**:
  - $P(A)$: Prior probability (our belief before seeing new data).
  - $P(B|A)$: Likelihood (probability of seeing evidence $B$ if hypothesis $A$ is true).
  - $P(B)$: Total evidence probability.
  - $P(A|B)$: Posterior probability (updated belief after seeing evidence $B$).

---

### 2.2 Repeated 3 Times

#### Question 5M-02: McCulloch-Pitts Neuron Model (AND Logic Function)
- **Exam Appearances**: Jun 2025 (Q.1a), Nov 2024 (Q.1c), Dec 2023 (Q.1c)
- **Verbatim Question**: "Implement AND function using Mc-Culloch-Pitts neuron? (take binary data) (05)"

**Simple Concept Summary for Students:**
- The McCulloch-Pitts neuron is the simplest mathematical model of a biological brain cell.
- Inputs $x_1, x_2 \in \{0, 1\}$ are multiplied by weights $w_1 = 1, w_2 = 1$.
- Total input: $I = x_1 w_1 + x_2 w_2$.
- Activation condition: Output $y = 1$ if $I \ge \theta$, otherwise $0$.
- For an **AND gate**, the threshold $\theta = 2$ because both inputs must be 1 ($1+1=2$) to activate output $y=1$.

#### Question 5M-03: Defuzzification (Definition, Necessity, and Centroid Method)
- **Exam Appearances**: May 2024 (Q.1b), Dec 2023 (Q.1b), Jun 2023 (Q.6c)
- **Verbatim Question**: "Define defuzzification and State the necessity of the defuzzification process. Describe the Centroid method with its formula. (05)"

**Simple Concept Summary for Students:**
- **What is Defuzzification?** Converting a fuzzy set (a range of membership values between 0 and 1) into a single, exact crisp number (such as "Rotate motor at 45 RPM").
- **Why is it necessary?** Real-world hardware and motors only understand exact voltages or RPM values, not fuzzy linguistic words like "Medium Speed".
- **Centroid Formula**:
  $$z^* = \frac{\sum z \cdot \mu(z)}{\sum \mu(z)}$$

---

### 2.3 Repeated 2 Times

| Question Topic | Exam Sessions | What to Write in the Answer |
| :--- | :--- | :--- |
| **Utility in Decision Theory** | Dec 2025 (Q.1a), Jun 2025 (Q.1e) | Define utility $U(s)$ as the measure of preference for a state. Write Principle of Maximum Expected Utility (MEU): Choose the action that maximizes $EU(a) = \sum P(s'\|a, e) U(s')$. |
| **Deterministic vs Probabilistic Reasoning** | Dec 2025 (Q.1b), Jun 2025 (Q.1b) | Deterministic logic assumes 100% certainty (true/false) and fails when facts are missing or sensors are noisy. Probabilistic reasoning uses degrees of belief to handle real-world uncertainty. |
| **Feedforward ANN vs RNN** | Dec 2025 (Q.1d), Jun 2025 (Q.1d) | ANN processes data in one forward direction with no memory of past inputs. RNN contains feedback loops and a hidden state vector $h_t$ to remember past sequential tokens (used in speech/NLP). |
| **Sampling Methods: Bootstrap & Holdout** | Nov 2024 (Q.1d), Jun 2023 (Q.6a) | Holdout splits data once into Train (70%) and Test (30%). Bootstrap samples $N$ rows with replacement (leaving $\approx 36.8\%$ Out-of-Bag data for testing). |

---

### 2.4 Single Appearance Questions

- **Markov Decision Process (MDP)** (Dec 2025 Q.1e): Define the 5 components: States $S$, Actions $A$, Transition probabilities $P(s'|s,a)$, Rewards $R$, and Discount factor $\gamma$.
- **Activation Functions** (Jun 2025 Q.1c): Explain Sigmoid (outputs 0 to 1), Tanh (outputs -1 to 1), and ReLU (outputs $\max(0, x)$ to prevent vanishing gradients).
- **Fuzziness vs Probability** (Jun 2025 Q.1f): Fuzziness is ambiguity about the nature of an event (degree of truth). Probability is uncertainty about whether an event will happen.
- **Fuzzy Set Operations** (Nov 2024 Q.1b): Algebraic sum ($A+B-AB$), Algebraic product ($AB$), Bounded sum ($\min(1, A+B)$), Bounded difference ($\max(0, A-B)$).
- **Deep Learning Applications** (May 2024 Q.1c): Image classification, voice assistants, autonomous driving, drug discovery.
- **Bagging vs Boosting** (May 2024 Q.1d): Bagging builds parallel independent trees to reduce variance. Boosting builds sequential dependent trees to reduce bias.
- **ROC Curves** (Dec 2023 Q.1d): A plot of True Positive Rate vs False Positive Rate at different decision thresholds. Area Under Curve (AUC) measures overall classifier quality.
- **Long Short-Term Memory (LSTM)** (Jun 2023 Q.6b): Explain why standard RNN fails (vanishing gradient) and how LSTM uses a memory cell with 3 gates.
- **Cognitive System Design Principles** (Jun 2023 Q.6d): Adaptive, Interactive, Iterative, Contextual.
- **Data Science for Text** (Jun 2023 Q.6f): Cleaning, tokenization, stop-word removal, TF-IDF vectorization, sentiment scoring.

---

## 3. Section 2: 10-Mark Questions (Ranked by Frequency)

---

### 3.1 Repeated 6 Times (100% Recurrence in All Papers)

#### Question 10M-01: Classifier Performance Metrics and Confusion Matrix Numericals
- **Exam Appearances**: Dec 2025 (Q.5a & Q.6b), Jun 2025 (Q.5a), Nov 2024 (Q.6a), May 2024 (Q.6a), Dec 2023 (Q.6a), Jun 2023 (Q.1a)
- **Verbatim Questions**:
  1. *Nov 2024 (Q.6a)*: "Define Accuracy, precision, and recall. Evaluate performance of classifier 1 and classifier 2 on the basis of above evaluation parameters, given following confusion matrix (Fraud detection). (10)"
  2. *May 2024 (Q.6a)*: "Calculate Accuracy, Precision, Recall and F1-score from the confusion matrix. (10)"
  3. *Dec 2023 (Q.6a)*: "Calculate Accuracy, Precision, Recall, Sensitivity and Specificity for Buys_Computer example. (10)"

**Key Formulas to Memorize for the Exam:**
- $\text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN}$ (Overall correct percentage)
- $\text{Precision} = \frac{TP}{TP + FP}$ (Out of all predicted positive, how many were truly positive)
- $\text{Recall / Sensitivity} = \frac{TP}{TP + FN}$ (Out of all actual positive cases, how many were detected)
- $\text{Specificity} = \frac{TN}{TN + FP}$ (Out of all actual negative cases, how many were correctly rejected)
- $\text{F1-Score} = 2 \cdot \frac{\text{Precision} \cdot \text{Recall}}{\text{Precision} + \text{Recall}}$ (Harmonic mean of Precision and Recall)

---

### 3.2 Repeated 5 Times

#### Question 10M-02: Convolutional Neural Network (CNN) Architecture
- **Exam Appearances**: Dec 2025 (Q.4a), Jun 2025 (Q.4a), May 2024 (Q.5b), Dec 2023 (Q.3a), Jun 2023 (Q.1b)
- **Verbatim Question**: "Explain Architecture of CNN in detail. What are the main components and how do they contribute to image recognition tasks? (10)"

**Simple Layer-by-Layer Architecture to Explain:**
1. **Input Layer**: Takes raw pixel matrix (e.g. $28 \times 28 \times 3$ for RGB images).
2. **Convolutional Layer**: Slips filter kernels across image to detect features (edges, corners, textures).
3. **Activation Layer (ReLU)**: Applies $f(x) = \max(0, x)$ to introduce non-linearity.
4. **Pooling Layer (Max Pooling)**: Reduces spatial dimensions (downsampling) to make the model invariant to slight shifts and reduce memory.
5. **Flattening**: Converts 2D feature maps into a 1D vector.
6. **Fully Connected (Dense) Layer**: Combines extracted features for final classification.
7. **Softmax Output Layer**: Converts final scores into class probabilities summing to 1.

#### Question 10M-03: Data Science for Multimodal Applications
- **Exam Appearances**: Dec 2025 (Q.6a), Jun 2025 (Q.6a), May 2024 (Q.6b), Dec 2023 (Q.6b), Jun 2023 (Q.5b)
- **Verbatim Question**: "Explain the role of machine learning in multimodal applications. Discuss how different data modalities (text, audio, image, and video) are integrated to improve performance and user experience. (10)"

**Simple Concept Summary for Students:**
- **What is Multimodal Data Science?** Combining information from multiple different formats (text subtitles, voice audio, image frames, video motions) rather than relying on a single data type.
- **Fusion Approaches**:
  - *Early Fusion*: Concatenate raw feature vectors before feeding them into a machine learning model.
  - *Late Fusion*: Train separate models for text, audio, and video, then combine their individual predictions using weighted voting.
  - *Hybrid Fusion*: Combine mid-level feature representations using deep neural network cross-attention layers.

---

### 3.3 Repeated 4 Times

#### Question 10M-04: Mamdani Fuzzy Controller Design (Washing Machine Problem)
- **Exam Appearances**: Dec 2025 (Q.3b), Jun 2025 (Q.3b), May 2024 (Q.4a), Jun 2023 (Q.4a)
- **Verbatim Question**: "Using Mamdani fuzzy model design a fuzzy model controller to determine the wash time of domestic washing machine. Assume inputs are dirt & grease on cloths. Use 3 descriptors for each input and 5 descriptors for output. Derive membership functions and fuzzy rules. (10)"

#### Question 10M-05: Ensemble Methods (Bagging, Boosting, Random Forest, AdaBoost)
- **Exam Appearances**: Dec 2025 (Q.5b), Jun 2025 (Q.5b), Nov 2024 (Q.2a), May 2024 (Q.2a), Dec 2023 (Q.2a), Jun 2023 (Q.2b)
- **Verbatim Question**: "How Bagging and Boosting handle bias-variance trade-off differently? Explain Random Forest and AdaBoost algorithms. (10)"

#### Question 10M-06: Cognitive Computing Systems (Principles and Architecture)
- **Exam Appearances**: Dec 2025 (Q.2a), Nov 2024 (Q.2b), May 2024 (Q.5a), Dec 2023 (Q.5a), Jun 2023 (Q.3b)
- **Verbatim Question**: "What is cognitive computing and how does it differ from traditional computing? List design principles and explain the process of building a cognitive application. (10)"

---

### 3.4 Repeated 3 Times

- **Taxonomies and Ontologies in Knowledge Representation** (Dec 2025 Q.2b, Jun 2025 Q.2b, Dec 2023 Q.2b): Explain hierarchical classification trees (Taxonomies) vs relational semantic graph networks with properties and axioms (Ontologies using RDF/OWL).
- **Bayesian Belief Networks (BBN)** (Jun 2025 Q.4b, Nov 2024 Q.4b, Dec 2023 Q.4b): Directed Acyclic Graphs (DAG) representing conditional dependencies between random variables and their Conditional Probability Tables (CPTs).

---

### 3.5 Repeated 2 Times

- **Fuzzy Membership Functions** (Dec 2025 Q.3a, Jun 2025 Q.3a): Triangular, Trapezoidal, Gaussian membership curves.
- **Defuzzification Methods (10M Theory)** (Jun 2025 Q.6b, Nov 2024 Q.4a): Centroid Method, Mean of Maxima (MOM), Smallest of Maxima (SOM), Largest of Maxima (LOM).
- **Artificial Neural Network (ANN) Components** (Jun 2025 Q.2a, Nov 2024 Q.3a): Input vector, synaptic weights, bias, summation function, activation function, output.
- **LSTM Architecture and Internal Gates** (Dec 2025 Q.4b, Nov 2024 Q.5b): Forget gate, Input gate, Cell state update, Output gate.
- **Autoencoders** (May 2024 Q.3a, Jun 2023 Q.4b): Encoder bottleneck ($z$) compression, Decoder reconstruction loss calculation.
- **Markov Decision Process (MDP)** (May 2024 Q.4b, Jun 2023 Q.3a): Value iteration, Policy iteration, Bellman optimality equation.
- **NLP in Cognitive Computing** (Dec 2025 Q.2a, Nov 2024 Q.5a): Tokenization, Named Entity Recognition (NER), Semantic intent classification.

---

### 3.6 Single Appearance Questions

- **XOR Logic with McCulloch-Pitts Neurons** (Jun 2023 Q.2a - 10M)
- **Cognitive Computing in Healthcare** (May 2024 Q.2b - 10M)
- **Data Science Applications in Industry** (May 2024 Q.3b - 10M)
- **Fuzzy Set Mathematical Properties** (Dec 2023 Q.4a - 10M)
- **Deep Learning Use Cases** (Dec 2023 Q.5b - 10M)
- **Class Imbalance and SMOTE Oversampling** (Jun 2023 Q.5a - 10M)
- **Video Recommendation Engine Case Study** (Nov 2024 Q.3b - 10M)
- **Book Recommendation Engine Case Study** (Dec 2023 Q.3b - 10M)
- **Data Science Trends for Audio** (Nov 2024 Q.6b - 10M)

---

## 4. Section 3: Step-by-Step Solved Numericals and Blueprints

### 4.1 How to Solve Confusion Matrix Numericals

**Example Problem (May 2024 Exam):**

| Actual / Predicted | Predicted Legitimate (Negative) | Predicted Fraudulent (Positive) | Total Actual |
| :--- | :---: | :---: | :---: |
| **Actual Legitimate (Negative)** | $TN = 850$ | $FP = 20$ | $870$ |
| **Actual Fraudulent (Positive)** | $FN = 30$ | $TP = 100$ | $130$ |
| **Total Predicted** | $880$ | $120$ | **Total $N = 1000$** |

**Step 1: Calculate Total Population ($N$)**
$$N = TP + TN + FP + FN = 100 + 850 + 20 + 30 = 1000$$

**Step 2: Calculate Accuracy**
$$\text{Accuracy} = \frac{TP + TN}{N} = \frac{100 + 850}{1000} = \frac{950}{1000} = 0.95 \quad (95.0\%)$$

**Step 3: Calculate Precision**
$$\text{Precision} = \frac{TP}{TP + FP} = \frac{100}{100 + 20} = \frac{100}{120} = 0.8333 \quad (83.33\%)$$

**Step 4: Calculate Recall / Sensitivity**
$$\text{Recall} = \frac{TP}{TP + FN} = \frac{100}{100 + 30} = \frac{100}{130} = 0.7692 \quad (76.92\%)$$

**Step 5: Calculate Specificity**
$$\text{Specificity} = \frac{TN}{TN + FP} = \frac{850}{850 + 20} = \frac{850}{870} = 0.9770 \quad (97.70\%)$$

**Step 6: Calculate F1-Score**
$$\text{F1-Score} = 2 \cdot \frac{\text{Precision} \cdot \text{Recall}}{\text{Precision} + \text{Recall}} = 2 \cdot \frac{0.8333 \cdot 0.7692}{0.8333 + 0.7692} = \frac{1.2816}{1.6025} = 0.7997 \quad (\approx 80\%)$$

---

### 4.2 How to Solve Bayes Theorem Medical Probability Problems

**Example Problem (Dec 2025 Exam):**
- Disease affects 1 in 10,000 people: Prior $P(D) = 0.0001$, so $P(\neg D) = 1 - 0.0001 = 0.9999$.
- Test accuracy is 99%: True Positive $P(+|D) = 0.99$, False Positive $P(+|\neg D) = 0.01$.
- Find the probability that a person who tests positive actually has the disease ($P(D|+)$).

**Step 1: Write Bayes' Formula**
$$P(D|+) = \frac{P(+|D) \cdot P(D)}{P(+)}$$

**Step 2: Calculate Total Probability of Testing Positive ($P(+)$)**
$$P(+) = P(+|D) \cdot P(D) + P(+|\neg D) \cdot P(\neg D)$$
$$P(+) = (0.99 \times 0.0001) + (0.01 \times 0.9999)$$
$$P(+) = 0.000099 + 0.009999 = 0.010098$$

**Step 3: Calculate Posterior Probability $P(D|+)$**
$$P(D|+) = \frac{0.000099}{0.010098} \approx 0.009804 \quad (0.98\%)$$

**Interpretation to write in exam:**
Even with a 99% accurate test, because the disease is extremely rare (1 in 10,000), a person testing positive only has a 0.98% chance of truly having the disease. The vast majority of positive tests are false positives from the healthy population.

---

### 4.3 How to Design a Mamdani Fuzzy Washing Machine Controller

1. **Input Variables and Linguistic Descriptors:**
   - **Input 1: Dirtiness of Clothes** = { Small (S), Medium (M), Large (L) }
   - **Input 2: Grease on Clothes** = { No Grease (NG), Medium Grease (MG), Large Grease (LG) }
2. **Output Variable:**
   - **Wash Time (Minutes)** = { Very Short (VS), Short (S), Medium (M), Long (L), Very Long (VL) }
3. **Fuzzy Rule Base Table ($3 \times 3 = 9$ Rules):**

| Dirtiness \ Grease | No Grease (NG) | Medium Grease (MG) | Large Grease (LG) |
| :--- | :---: | :---: | :---: |
| **Small (S)** | Very Short (VS) | Short (S) | Medium (M) |
| **Medium (M)** | Short (S) | Medium (M) | Long (L) |
| **Large (L)** | Medium (M) | Long (L) | Very Long (VL) |

4. **Rule Execution Steps:**
   - Step 1: Fuzzify crisp inputs using triangular membership functions.
   - Step 2: Apply fuzzy AND operator ($\min(\mu_{\text{Dirt}}, \mu_{\text{Grease}})$).
   - Step 3: Aggregate outputs using fuzzy OR operator ($\max$).
   - Step 4: Defuzzify using the Centroid method to calculate exact wash duration in minutes.

---

## 5. Section 4: 3-Hour Exam Strategy

To maximize your score out of 80:

```text
Time Block 1 (00:00 - 00:45) -> Q.3: Mamdani Fuzzy Controller Design (20 Marks)
Time Block 2 (00:45 - 01:30) -> Q.6 or Q.5: Confusion Matrix Numerical + Multimodal (20 Marks)
Time Block 3 (01:30 - 02:15) -> Q.4: CNN Architecture Diagram + Ensemble Methods (20 Marks)
Time Block 4 (02:15 - 03:00) -> Q.1: Compulsory 5-Mark Questions (Bayes, ANN, Sampling) (20 Marks)
```
