# 🌌 **⚡ Probability & Statistics — Ultimate Cheat Sheet**

---

# 🧩 **1. Set & Probability Basics**

- Union (A ∪ B) → “A or B”
- Intersection (A ∩ B) → “A and B”
- Complement (Aᶜ) → “not A”

### Core Formulas

- P(A ∪ B) = P(A) + P(B) − P(A ∩ B)
- P(Aᶜ) = 1 − P(A)

---

# 🎯 **2. Conditional Probability & Bayes**

### Conditional

- P(A | B) = P(A ∩ B) / P(B)

### Bayes

- P(A | B) = [P(B | A) × P(A)] / P(B)

---

💡 **When to use:**

- Given result → find cause → use **Bayes**

---

# 🔢 **3. Counting (Very Important)**

### Combination (no order)

- nCk = n! / (k!(n−k)!)

### Permutation (order matters)

- nPk = n! / (n−k)!

---

💡 Trick:

- “Committee” → combination
- “Roles / positions” → permutation

---

# 🎲 **4. Discrete Distributions**

---

## 🌸 Bernoulli(p)

- Values: 0 or 1
- E[X] = p
- Var(X) = p(1−p)

---

## 🌸 Binomial(n, p)

- Repeated trials
- E[X] = np
- Var(X) = np(1−p)

---

## 🌸 Geometric(p)

- First success at trial k
- P = (1−p)^(k−1) × p

💡 Memoryless!

---

## 🌸 Negative Binomial

- k-th success at trial n

---

## 🌸 Poisson(λ)

- Rare events
- P(X=k) = (λ^k e^(−λ)) / k!
- E[X] = Var(X) = λ

---

💡 **When to use Poisson:**

- Large n, small p → np = λ

---

# 🌊 **5. Continuous Distributions**

---

## 🌸 Uniform(a,b)

- Flat distribution
- P = (interval length) / (total length)

---

## 🌸 Exponential(λ)

- Waiting time
- E[X] = 1/λ
- P(X > x) = e^(−λx)

💡 Memoryless!

---

## 🌸 Gamma(k, λ)

- Sum of k exponentials
- E[X] = k/λ

---

## 🌸 Normal N(μ, σ²)

- Bell curve
- Standardize:

Z = (X − μ) / σ

---

💡 Key value:

- P(|Z| < 1) ≈ 0.6826

---

# 🔗 **6. Expectation & Variance**

### Expectation

- E[X] = Σ xP(x)

### Variance

- Var(X) = E[X²] − (E[X])²

---

💡 Linearity:

- E[aX + bY] = aE[X] + bE[Y]

---

# 🔗 **7. Joint Distribution**

### Covariance

- Cov(X,Y) = E[XY] − E[X]E[Y]

---

### Correlation

- ρ = Cov / (σX × σY)

---

💡 Independence:

- If independent → P(X,Y) = P(X)P(Y)
- Also → Cov = 0 (but reverse not always true!)

---

# 📈 **8. CDF & PDF**

- PDF → density
- CDF → accumulated probability

### Relationship

- CDF = integral of PDF
- PDF = derivative of CDF

---

# 📊 **9. Law of Large Numbers (LLN)**

- Sample mean → true mean
- More data = more accuracy

---

# 🌌 **10. Central Limit Theorem (CLT)**

- Sample mean becomes normal

Standard form:

(X̄ − μ) / (σ / √n) → N(0,1)

---

💡 Works even if original distribution is NOT normal!

---

# ⚔️ **Exam Strategy (Very Important)**

✨ Identify keywords:

- “At least” → complement
- “Given” → conditional / Bayes
- “Number of events” → Poisson
- “First success” → Geometric
- “k-th success” → Negative Binomial
- “Waiting time” → Exponential
