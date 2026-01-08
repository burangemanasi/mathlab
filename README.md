# Math Lab (Linear Algebra + Probability) — FAANG-Level Problem Set

**Goal:** Consolidate Week 2 with derivations + short computational checks.

**Outcome:** Students can derive key results, verify with small code experiments, and communicate clearly under interview constraints.

---

# How to Start

1. **Fork** this repository.  
2. Open `math_student_lab.ipynb` in **Google Colab**.  
3. Complete derivations + TODO code.  
4. **Restart runtime → Run All** cells.  
5. Push changes and submit a **Pull Request**.  

⚠️ **Do NOT edit notebooks directly on GitHub.**

---

## Lab Rules (FAANG Style)

- ✅ Show steps (but be concise)
- ✅ Validate with a small numeric experiment
- ✅ Call out assumptions

---

# Notebook Rules

- Do **NOT** rename the notebook  
- Do **NOT** delete TODOs  
- Do **NOT** hardcode outputs  
- Notebook must run **top-to-bottom**  

---

# Dataset

- Synthetic matrices/vectors and toy probability setups

## Why?

- Keeps focus on derivation + verification
- Mirrors interview whiteboard + quick sanity check workflow

---

## Section 1 — Projection Matrices

### Task 1.1: Prove/verify projection properties

**Checkpoint Questions:**

- What does idempotent mean?
- Why is orthogonal projection symmetric?

---

## Section 2 — Positive Semidefinite (PSD) Matrices

### Task 2.1: Show X^T X is PSD

**Interview Angle:**

- Where does PSD show up in ML (covariance, kernels)?

---

## Section 3 — Least Squares

### Task 3.1: Derive normal equations + verify numerically

**FAANG Gotcha:**

- Avoid matrix inverse; use solve/lstsq.

---

## Section 4 — Bayes + Base Rate

### Task 4.1: Derive P(D|+) + simulate

**Checkpoint Questions:**

- Why does base rate dominate when prevalence is low?

---

## Section 5 — PCA Link

### Task 5.1: Covariance eigenvectors vs SVD directions

**Interview Angle:**

- How does PCA relate to embeddings and compression?

---

## Submission Expectations

Students must submit:

- Derivations written clearly
- TODO code complete
- Checks passing

---

## FAANG Interview Evaluation Rubric

| Skill                     | Evaluated |
|---------------------------|-----------|
| Derivation correctness     | ✅        |
| Verification discipline    | ✅        |
| ML intuition               | ✅        |
| Explanation clarity        | ✅        |

## Topics

- Linear algebra: projections, orthogonality, PSD matrices
- Probability: expectation, variance, Bayes
- ML links: least squares, PCA, Naive Bayes
