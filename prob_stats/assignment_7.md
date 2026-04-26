# 📘 **Assignment 7**

## 🌸 **Q1 (1) Poisson: Exactly 3 calls**

Given:

- Average = 4 calls/day → λ = 4

Use Poisson:

P(X = k) = (λ^k × e^(−λ)) / k!

---

### Step-by-step

- λ = 4, k = 3
- 4³ = 64
- 3! = 6
- e^(−4) ≈ 0.0183

Now:

- (64 / 6) × 0.0183 ≈ **0.195**

---

✅ **Answer: ≈ 0.195**

---

## 🌸 **Q1 (2) First call at time 3**

👉 This is **Geometric Distribution**

Because:

- We are counting **time until first success**

---

Formula idea:

P(first success at k) = (1−p)^(k−1) × p

---

But here’s the subtle part 💡

Poisson (λ = 4 per day) → convert to probability per time unit:

👉 Assume 1 day = 1 unit → probability of a call in a small unit ≈ 4 events / time

For simplicity in discrete modeling, we approximate:

- p ≈ 4 / (large time scale) → but commonly in such problems, we assume a **given success probability**

⚠️ Since p is not explicitly given, we interpret conceptually:

---

### Final (conceptual answer)

- Distribution: **Geometric**
- Formula: (1−p)² × p

(If p were known, you plug it in)

---

## 🌸 **Q1 (3) Poisson vs Geometric**

✨ **Key Differences:**

| Aspect    | Poisson              | Geometric              |
| --------- | -------------------- | ---------------------- |
| Purpose   | Count events in time | Time until first event |
| Variable  | Number of calls      | Number of trials       |
| Parameter | λ (rate)             | p (success prob)       |
| Memory    | Not memoryless       | Memoryless             |

---

💡 Intuition:

- Poisson → “How many calls today?”
- Geometric → “How long until first call?”

---

# 📘 **Part 2: Continuous Distributions**

## 🌸 **Q2 (1) Mean lifetime**

Exponential mean:

- E[X] = 1 / λ
- = 1 / 0.5 = **2**

---

✅ **Answer: 2 time units**

---

## 🌸 **Q2 (2) P(X > 5)**

Formula:

- P(X > x) = e^(−λx)

---

- e^(−0.5 × 5) = e^(−2.5) ≈ **0.0821**

---

✅ **Answer: ≈ 0.082**

---

## 🌸 **Q2 (3) Exponential vs Gamma**

💡 Relationship:

- Exponential = special case of Gamma

---

✨ Specifically:

- Gamma(k, λ) = sum of k exponential variables
- If k = 1 → Gamma becomes Exponential

---

💡 Intuition:

- Exponential → waiting for **1 event**
- Gamma → waiting for **k events**

---

# 📘 **Part 3: Joint Distribution**

Given:

f(x,y) = 2 for 0 < x < y < 1

---

## 🌸 **Q3 (1) Marginal fX(x)**

We integrate over y:

- y goes from x → 1

---

So:

- fX(x) = ∫ from x to 1 of 2 dy
- = 2(1 − x)

---

✅ **Answer: fX(x) = 2(1 − x), for 0 < x < 1**

---

## 🌸 **Q3 (2) Conditional fY|X(y|x)**

Formula idea:

- f(Y|X) = joint / marginal

---

So:

- = 2 / [2(1 − x)]
- = **1 / (1 − x)**

---

Valid for:

- x < y < 1

---

✅ **Answer: fY|X(y|x) = 1 / (1 − x)**

---

## 🌸 **Q3 (3) Independence?**

👉 Check:

Independent if:

f(x,y) = fX(x) × fY(y)

---

But:

- f(x,y) = 2
- fX(x) × fY(y) = depends on x and y

❌ Not equal

---

Also:

- Region constraint: x < y

👉 This alone breaks independence

---

✅ **Answer: NOT independent**

---

# 🌟 **Key Takeaways (High-Level Insight 💎)**

- Poisson → counting events
- Geometric → waiting time (discrete)
- Exponential → waiting time (continuous)
- Gamma → multiple waiting events
- Joint distributions → always check region constraints
- Independence fails if variables are “linked” by conditions
