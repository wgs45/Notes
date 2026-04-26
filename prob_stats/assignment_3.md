# 📘 **Assignment 3**

A factory has three production lines (A1, A2, A3), with production proportions as follows:

- P(A1) = 0.5
- P(A2) = 0.3
- P(A3) = 0.2

The defect rates of each production line are:

- P(D | A1) = 0.02
- P(D | A2) = 0.04
- P(D | A3) = 0.05

Where:

- D = the product is defective

---

Please answer the following questions:

### (1)

Find the probability that a randomly selected product is defective:
P(D)
_(Use the Law of Total Probability)_

---

### (2)

P(A3 | D)
_(Use Bayes’ Theorem)_

Given that the selected product is defective, find the probability that it came from production line A3.

---

### (3)

Determine whether events A3 and D are independent.

---

# ✨ **Solutions + Step-by-Step Explanation**

## 🌸 **(1) Find P(D) — Law of Total Probability**

Think of it like this:

A defective product can come from **any of the three lines**, so we sum all possibilities:

P(D) =
P(A1) × P(D|A1) +
P(A2) × P(D|A2) +
P(A3) × P(D|A3)

---

### Step-by-step

- From A1: 0.5 × 0.02 = 0.01
- From A2: 0.3 × 0.04 = 0.012
- From A3: 0.2 × 0.05 = 0.01

Now add them:

- 0.01 + 0.012 + 0.01 = **0.032**

---

✅ **Final Answer: P(D) = 0.032**

---

## 🌸 **(2) Find P(A3 | D) — Bayes’ Theorem**

Now we reverse the perspective:

👉 “Given that it is defective, what is the chance it came from A3?”

---

### Formula idea

P(A3 | D) =
[ P(A3) × P(D | A3) ] / P(D)

---

### Step-by-step

- Numerator: 0.2 × 0.05 = 0.01
- Denominator: P(D) = 0.032

So:

- 0.01 / 0.032 = **0.3125**

---

✅ **Final Answer: P(A3 | D) = 0.3125 (≈ 31.25%)**

---

## 🌸 **(3) Are A3 and D independent?**

### 💡 Key idea

Two events are independent if:

P(A3 ∩ D) = P(A3) × P(D)

---

### Step 1: Compute left side

P(A3 ∩ D) =
P(A3) × P(D | A3)
= 0.2 × 0.05 = **0.01**

---

### Step 2: Compute right side

P(A3) × P(D) =
0.2 × 0.032 = **0.0064**

---

### Step 3: Compare

- Left side = 0.01
- Right side = 0.0064

They are **NOT equal**

---

❌ Therefore:

A3 and D are **NOT independent**

---

💡 **Meaning in real life:**

- The probability of defect **depends on which production line it came from**
- So knowing A3 **changes** the chance of defect

---

# 🌟 **Key Takeaways (Very Important 💎)**

- Law of Total Probability → “combine all possible sources”
- Bayes’ Theorem → “reverse conditional probability”
- Independence → check if:
  “joint = product of individual probabilities”
