# 📘 **Assignment 6**

## **I. Discrete Distributions**

### **1. Bernoulli Distribution**

A self-driving system recognizes lane lines correctly with probability p = 0.92 in a single attempt.
(X ~ Bernoulli(p))

1. Find P(X = 0)
2. Find expectation and variance

---

### **2. Binomial Distribution**

Tested 10 times, each with success probability 0.92.
(X ~ Binomial(10, 0.92))

1. Find probability of 9 successes
2. Find expectation

---

### **3. Geometric Distribution**

Success probability = 0.3
Find probability that the **first success occurs on the 3rd trial**

---

### **4. Negative Binomial Distribution**

Success probability = 0.3
Find probability that the **5th success occurs on the 8th trial**

---

### **5. Poisson Distribution**

λ = 2
Find P(X = 3)

---

## **II. Continuous Distributions**

### **6. Uniform Distribution**

X ~ U(0,10)
Find P(2 ≤ X ≤ 5)

---

### **7. Exponential Distribution**

λ = 0.5
Find P(X > 3)

---

### **8. Gamma Distribution**

k = 3, λ = 0.5
Find expectation

---

### **9. Normal Distribution**

X ~ N(0,1)
Find P(|X| < 1)

---

# ✨ **Step-by-Step Solutions**

---

## 🌸 **1. Bernoulli**

### (1) P(X = 0)

- Failure = 1 − p
- = 1 − 0.92 = **0.08**

---

### (2) Expectation & Variance

- E[X] = p = **0.92**
- Var(X) = p(1−p) = 0.92 × 0.08 = **0.0736**

---

## 🌸 **2. Binomial**

### (1) P(X = 9)

Use combination idea:

- C(10,9) = 10
- Probability = 10 × (0.92)^9 × (0.08)^1

Approx:

- (0.92)^9 ≈ 0.472
- Multiply: 10 × 0.472 × 0.08 ≈ **0.378**

---

### (2) Expectation

- E[X] = n × p = 10 × 0.92 = **9.2**

---

## 🌸 **3. Geometric**

Formula idea:

P(first success at k) = (1−p)^(k−1) × p

---

For k = 3:

- = (0.7)^2 × 0.3
- = 0.49 × 0.3 = **0.147**

---

## 🌸 **4. Negative Binomial**

We want 5th success at 8th trial:

- Choose positions of first 4 successes among first 7 trials
  → C(7,4) = 35

Now multiply:

- 35 × (0.3)^5 × (0.7)^3

Approx:

- (0.3)^5 ≈ 0.00243
- (0.7)^3 ≈ 0.343

Multiply:

- 35 × 0.00243 × 0.343 ≈ **0.0292**

---

## 🌸 **5. Poisson**

Formula idea:

P(X=k) = (λ^k × e^(-λ)) / k!

---

For k=3:

- (2^3 / 6) × e^(-2)
- = (8/6) × 0.1353 ≈ **0.180**

---

## 🌸 **6. Uniform**

Uniform means flat probability:

- Length of interval / total length

---

- (5 − 2) / (10 − 0) = 3 / 10 = **0.3**

---

## 🌸 **7. Exponential**

Formula:

P(X > x) = e^(−λx)

---

- e^(−0.5 × 3) = e^(−1.5) ≈ **0.223**

---

## 🌸 **8. Gamma**

Expectation:

- E[X] = k / λ

---

- = 3 / 0.5 = **6**

---

## 🌸 **9. Normal (Standard Normal)**

We want:

P(|X| < 1)

👉 Equivalent to:

P(−1 < X < 1)

---

From standard normal table:

- ≈ **0.6826**

---

# 🌟 **Final Answers Summary**

| Distribution      | Answer   |
| ----------------- | -------- |
| Bernoulli P(X=0)  | 0.08     |
| Bernoulli Var     | 0.0736   |
| Binomial P(X=9)   | ≈ 0.378  |
| Binomial E[X]     | 9.2      |
| Geometric         | 0.147    |
| Negative Binomial | ≈ 0.0292 |
| Poisson           | ≈ 0.180  |
| Uniform           | 0.3      |
| Exponential       | ≈ 0.223  |
| Gamma E[X]        | 6        |
| Normal            | ≈ 0.6826 |

---

# 🌟 **Key Takeaways (Your Exam Weapons 💎)**

- Bernoulli → single trial
- Binomial → fixed number of trials
- Geometric → first success
- Negative Binomial → kth success
- Poisson → rare events over time
- Uniform → equal probability
- Exponential → waiting time
- Gamma → sum of exponentials
- Normal → symmetric bell curve
