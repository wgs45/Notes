# 📘 **Assignment 4**

**Homework Problem**

Let the random variable **X** have the following probability density function (PDF):

f(x) = 2x, for 0 ≤ x ≤ 1
f(x) = 0, otherwise

Answer the following questions:

1. Determine whether **X** is a discrete random variable or a continuous random variable.
2. Verify whether f(x) is a valid PDF.
3. Find the cumulative distribution function (CDF) F(x) of X.
4. Find the probability:
   P(0.3 < X < 0.8)
5. Explain the basic properties of the CDF.

---

# ✨ **Solutions + Step-by-Step Explanation**

## 🌸 **(1) Discrete or Continuous?**

👉 Since we are given a **probability density function (PDF)**:

- PDF → used for **continuous random variables**

✅ **Answer: X is a continuous random variable**

---

## 🌸 **(2) Is f(x) a valid PDF?**

To be valid, two conditions must hold:

### ✅ Condition 1: f(x) ≥ 0

- f(x) = 2x
- On [0,1], x ≥ 0 → so 2x ≥ 0 ✔️

---

### ✅ Condition 2: Total area = 1

We integrate 2x from 0 to 1:

\int\_{0}^{1} 2x , dx = 1

✔️ The total probability is 1

---

✅ **Answer: Yes, f(x) is a valid PDF**

---

## 🌸 **(3) Find the CDF F(x)**

CDF means:

👉 “Probability that X is less than or equal to x”

We integrate the PDF from 0 to x:

---

### Case-by-case result

- If x < 0 → F(x) = 0
- If 0 ≤ x ≤ 1 → F(x) = x²
- If x > 1 → F(x) = 1

---

💡 So the full answer:

F(x) =

- 0 (x < 0)
- x² (0 ≤ x ≤ 1)
- 1 (x > 1)

---

## 🌸 **(4) Find P(0.3 < X < 0.8)**

Use CDF:

👉 P(a < X < b) = F(b) − F(a)

---

### Step-by-step

- F(0.8) = (0.8)² = 0.64
- F(0.3) = (0.3)² = 0.09

Subtract:

- 0.64 − 0.09 = **0.55**

---

✅ **Final Answer: 0.55**

---

## 🌸 **(5) Basic Properties of CDF**

A CDF always has these properties:

### 💡 1. Non-decreasing

- It never goes down
- As x increases, probability accumulates

---

### 💡 2. Range between 0 and 1

- 0 ≤ F(x) ≤ 1

---

### 💡 3. Limits

- As x → −∞ → F(x) → 0
- As x → +∞ → F(x) → 1

---

### 💡 4. Right-continuous

- No sudden jumps from the right side

---

### 💡 5. Relationship with PDF

- PDF is the derivative of CDF
- CDF is the integral of PDF

---

# 🌟 **Key Takeaways (Very Important 💎)**

- PDF → describes density (not direct probability!)
- CDF → accumulates probability
- Probability = **area under curve**
- For continuous variables:
  👉 P(X = exact value) = 0
