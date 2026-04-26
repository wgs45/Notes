# 📘 **Assignment 5**

Let the joint distribution of random variables **(X, Y)** be:

| x \ y | 0   | 1   |
| ----- | --- | --- |
| 0     | 0.2 | 0.3 |
| 1     | 0.1 | 0.4 |

---

### **Questions**

1. Find E[X] and E[Y]
2. Find E[XY]
3. Find Var(X) and Var(Y)
4. Find Cov(X, Y)
5. Find the correlation coefficient ρ(X, Y)
6. Using linearity of expectation, compute E[3X + 2Y]
7. Determine whether (X, Y) are independent

---

# ✨ **Step-by-Step Solutions**

## 🌸 **Step 0: Marginal Probabilities (Very Important!)**

First, sum rows and columns:

### For X

- P(X=0) = 0.2 + 0.3 = 0.5
- P(X=1) = 0.1 + 0.4 = 0.5

---

### For Y

- P(Y=0) = 0.2 + 0.1 = 0.3
- P(Y=1) = 0.3 + 0.4 = 0.7

---

## 🌸 **(1) E[X], E[Y]**

### E[X]

- = 0×0.5 + 1×0.5 = **0.5**

---

### E[Y]

- = 0×0.3 + 1×0.7 = **0.7**

---

✅ **Answers:**

- E[X] = 0.5
- E[Y] = 0.7

---

## 🌸 **(2) E[XY]**

Use joint probabilities:

- (0×0×0.2) = 0
- (0×1×0.3) = 0
- (1×0×0.1) = 0
- (1×1×0.4) = 0.4

---

👉 Sum:

- E[XY] = **0.4**

---

## 🌸 **(3) Variance**

### Var(X)

First compute E[X²]:

- = 0²×0.5 + 1²×0.5 = 0.5

Now:

- Var(X) = E[X²] − (E[X])²
- = 0.5 − (0.5)² = 0.5 − 0.25 = **0.25**

---

### Var(Y)

E[Y²]:

- = 0²×0.3 + 1²×0.7 = 0.7

Now:

- Var(Y) = 0.7 − (0.7)²
- = 0.7 − 0.49 = **0.21**

---

✅ **Answers:**

- Var(X) = 0.25
- Var(Y) = 0.21

---

## 🌸 **(4) Cov(X, Y)**

Formula idea:

Cov(X,Y) = E[XY] − E[X]E[Y]

---

- = 0.4 − (0.5 × 0.7)
- = 0.4 − 0.35 = **0.05**

---

✅ **Answer: 0.05**

---

## 🌸 **(5) Correlation ρ(X, Y)**

Formula idea:

ρ = Cov / (√Var(X) × √Var(Y))

---

### Step-by-step

- √0.25 = 0.5
- √0.21 ≈ 0.458

Multiply:

- 0.5 × 0.458 ≈ 0.229

Now:

- 0.05 / 0.229 ≈ **0.218**

---

✅ **Answer: ρ ≈ 0.218**

---

💡 Interpretation:

- Positive but weak correlation

---

## 🌸 **(6) E[3X + 2Y]**

Linearity of expectation:

- E[3X + 2Y] = 3E[X] + 2E[Y]

---

- = 3×0.5 + 2×0.7
- = 1.5 + 1.4 = **2.9**

---

✅ **Answer: 2.9**

---

## 🌸 **(7) Independence Check**

👉 Key condition:

X and Y are independent if:

P(X=x, Y=y) = P(X=x) × P(Y=y)

---

Check one case:

- P(0,0) = 0.2
- P(X=0)×P(Y=0) = 0.5×0.3 = 0.15

❌ Not equal → NOT independent

---

✅ **Final Answer: X and Y are NOT independent**

---

# 🌟 **Key Takeaways (Exam Core 💎)**

- Always compute **marginals first**
- E[XY] uses **joint distribution**
- Cov = “relationship strength”
- Correlation = “normalized covariance”
- Independence → check product rule
