# 📘 **Assignment 8**

## **Part 1: Problems**

---

### **Question 1 (Sets and Events)**

Let the sample space:

S = {1, 2, 3, 4, 5, 6}

represent the outcome of rolling a fair die.

Let events:

A = {2, 4, 6},
B = {2, 3, 5}

Find:

1. A ∪ B
2. A ∩ B
3. Aᶜ
4. P(A)

---

### **Question 2 (Permutations & Combinations)**

From 8 students, choose:

1. 3 people to form a committee (no positions)
2. 3 people to serve as class leader, vice leader, and academic officer (positions matter)

How many ways for each?

---

### **Question 3 (Conditional Probability)**

In a factory:

- 60% of products come from Machine A
- 40% come from Machine B

Given:

- Defect rate of A = 2%
- Defect rate of B = 5%

If a randomly selected product is defective, find the probability that it came from Machine B.

---

### **Question 4 (CDF / PMF)**

Discrete random variable X has PMF:

- P(X=1) = k
- P(X=2) = 2k
- P(X=3) = 3k

Find:

1. Constant k
2. P(X ≤ 2)
3. CDF F(2)

---

### **Question 5 (Expectation & Variance)**

| x   | 0   | 1   | 2   |
| --- | --- | --- | --- |
| P   | 0.2 | 0.5 | 0.3 |

Find:

1. E(X)
2. E(X²)
3. Var(X)

---

### **Question 6 (Binomial Distribution)**

Each question has probability 0.8 of being correct, total 5 questions. Let X = number of correct answers.

Find:

1. Distribution name and parameters
2. P(X = 4)

---

### **Question 7 (Poisson Distribution)**

A call center receives 3 calls per hour on average. Let X = number of calls per hour.

Find:

1. Distribution of X
2. P(X = 2)

---

### **Question 8 (Normal Distribution)**

X ~ N(100,16)

Find:

1. Mean
2. Standard deviation
3. After standardization, express P(X < 104) in standard normal form

---

### **Question 9 (Law of Large Numbers)**

Let X₁, X₂, …, Xₙ be i.i.d. random variables:

- E(Xi) = μ
- Var(Xi) = σ² < ∞

Sample mean:

X̄ = (1/n) Σ Xi

Explain:

1. Law of Large Numbers
2. Its meaning in statistical inference

---

### **Question 10 (Central Limit Theorem)**

Same assumptions as above.

Explain when n → ∞:

(X̄ − μ) / (σ / √n)

What distribution does it approach? Explain its meaning.

---

# ✨ **Solutions + Explanations**

---

## 🌸 **Q1: Sets**

1. A ∪ B = {2,3,4,5,6}
2. A ∩ B = {2}
3. Aᶜ = {1,3,5}
4. P(A) = 3/6 = **0.5**

💡 Because 3 favorable outcomes out of 6 total.

---

## 🌸 **Q2: Counting**

1. Committee (no order):
   = 8C3 = **56**

2. With positions:
   = 8P3 = 8×7×6 = **336**

---

## 🌸 **Q3: Bayes**

Step 1: Total defective:

- A: 0.6×0.02 = 0.012
- B: 0.4×0.05 = 0.02

Total = 0.032

---

Step 2:

- P(B | D) = 0.02 / 0.032 = **0.625**

---

## 🌸 **Q4: PMF**

1. k + 2k + 3k = 1 → 6k = 1 → k = **1/6**

---

1. P(X ≤ 2) = k + 2k = 3k = **1/2**

---

1. F(2) = **1/2**

---

## 🌸 **Q5: Expectation & Variance**

E(X):

- 0×0.2 + 1×0.5 + 2×0.3 = **1.1**

---

E(X²):

- 0 + 1×0.5 + 4×0.3 = 0.5 + 1.2 = **1.7**

---

Var(X):

- 1.7 − (1.1)² = 1.7 − 1.21 = **0.49**

---

## 🌸 **Q6: Binomial**

1. X ~ Binomial(5, 0.8)

---

1. P(X=4):

- C(5,4)=5
- ≈ 5 × (0.8)^4 × (0.2) ≈ **0.4096**

---

## 🌸 **Q7: Poisson**

1. X ~ Poisson(3)

---

1. P(X=2):

- ≈ (9/2) × e^(−3) ≈ **0.224**

---

## 🌸 **Q8: Normal**

1. Mean = **100**
2. Std dev = √16 = **4**

---

1. Standardize:

- Z = (104 − 100) / 4 = **1**

👉 So:

P(X < 104) = P(Z < 1)

---

## 🌸 **Q9: Law of Large Numbers**

1. As n increases, sample mean X̄ → true mean μ

2. Meaning:

- More data → more accurate estimate

---

## 🌸 **Q10: Central Limit Theorem**

1. Distribution → **Standard Normal N(0,1)**

---

1. Meaning:

- Regardless of original distribution
- Sample mean becomes **normal when n is large**

---

# 🌟 **Final Insight (Very Important 💎)**

- LLN → “converges to truth”
- CLT → “distribution becomes normal”
- Together → foundation of statistics
