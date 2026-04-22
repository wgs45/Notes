# 📊 Probability Midterm Exam (Weeks 1–8)

---

## 📌 Instructions

This exam contains 14 questions. Each question is worth 7 points (Question 14 is worth 9 points, total = 100 points).
Please write the letter corresponding to the correct answer inside the parentheses before each question.

※ Notation: The normal distribution is written as N(μ, σ²), where the second parameter represents the variance.

---

## 📝 Questions

### ( ) 1

A fair 8-sided die is rolled, with sample space
S = {1, 2, 3, 4, 5, 6, 7, 8}.
Let events A = {1, 3, 5, 7}, B = {2, 3, 5, 7}.
Which of the following statements is incorrect?

(A) A ∪ B = {1, 2, 3, 5, 7}
(B) A ∩ B = {3, 5}
(C) Aᶜ = {2, 4, 6, 8}
(D) P(A) = 1/2

---

### ( ) 2

From 10 students, choose 4 to form a committee (no positions).
How many ways are there?

(A) 120 (B) 210 (C) 5040 (D) 10000

---

### ( ) 3

From 10 students, choose 4 to serve as class leader, vice leader, academic officer, and discipline officer.
How many arrangements are there?

(A) 210 (B) 2520 (C) 5040 (D) 10000

---

### ( ) 4

In a factory, 70% of products come from Machine A, and 30% come from Machine B.
The defect rate of Machine A is 3%, and the defect rate of Machine B is 8%.
If a defective item is selected at random, what is the probability that it came from Machine B?

(A) 0.240 (B) 0.467 (C) 0.533 (D) 0.700

---

### ( ) 5

A discrete random variable X has probability mass function
P(X = x) = k·x, x = 1, 2, 3, 4.
Find the value of k.

(A) 1/6 (B) 1/8 (C) 1/10 (D) 1/12

---

### ( ) 6

Continuing from the previous question, find the cumulative distribution function
F(3) = P(X ≤ 3).

(A) 0.3 (B) 0.4 (C) 0.6 (D) 0.9

---

### ( ) 7

A random variable X has the following distribution:

| x        | 0   | 1   | 2   | 3   |
| -------- | --- | --- | --- | --- |
| P(X = x) | 0.1 | 0.3 | 0.4 | 0.2 |

Find E(X).

(A) 1.3 (B) 1.5 (C) 1.7 (D) 2.0

---

### ( ) 8

Continuing from the previous question, find Var(X).

(A) 0.61 (B) 0.81 (C) 1.00 (D) 1.21

---

### ( ) 9

For a multiple-choice question, the probability of answering correctly is 0.7.
A total of 6 questions are answered. Let X = number of correct answers.
Find P(X = 4).

(A) 0.185 (B) 0.324 (C) 0.412 (D) 0.500

---

### ( ) 10

A customer service center receives an average of 4 calls per hour.
Let X be the number of calls received in one hour.
Find P(X = 3).

(A) 0.147 (B) 0.195 (C) 0.224 (D) 0.275

---

### ( ) 11

Let X ~ N(120, 25) (where the second parameter is the variance σ²).
Which of the following is correct?

(A) Mean = 120, Standard deviation = 25
(B) Mean = 120, Standard deviation = 5
(C) Mean = 25, Standard deviation = 120
(D) Mean = 5, Standard deviation = 120

---

### ( ) 12

Continuing from the previous question, after standardization,
P(X < 125) should be expressed as which of the following?

(A) P(Z < 0.5)
(B) P(Z < 1)
(C) P(Z < 2)
(D) P(Z < 5)

---

### ( ) 13

Let X₁, X₂, …, Xₙ be independent and identically distributed random variables, and
E(Xᵢ) = μ, Var(Xᵢ) = σ² < ∞.
Let the sample mean X̄ₙ = (1/n) Σ Xᵢ.
According to the Law of Large Numbers (LLN), which statement is correct?

(A) As n → ∞, X̄ₙ converges to 0
(B) As n → ∞, X̄ₙ converges to μ
(C) As n → ∞, X̄ₙ converges to σ²
(D) X̄ₙ is always equal to μ, independent of n

---

### ( ) 14

Continuing from the previous setting, according to the Central Limit Theorem (CLT),
as n → ∞, the distribution of
(X̄ₙ − μ) / (σ / √n)
approaches which of the following?

(A) Standard normal distribution N(0, 1)
(B) Poisson distribution Poisson(μ)
(C) Normal distribution N(μ, σ²)
(D) Binomial distribution B(n, p)

---

# ✅ Instructor Reference Answers + Explanations

---

### 1️⃣ (B)

A ∩ B should be {3, 5, 7}.
Option (B) misses 7, so it is incorrect.

---

### 2️⃣ (B)

This is a combination (order does not matter):
C(10,4) = 210

---

### 3️⃣ (C)

This is a permutation (order matters):
P(10,4) = 10×9×8×7 = 5040

---

### 4️⃣ (C)

Using conditional probability:
P(B | defective) = (0.3×0.08) / (0.7×0.03 + 0.3×0.08) ≈ 0.533

---

### 5️⃣ (C)

Total probability must equal 1:
k(1+2+3+4) = 10k = 1 → k = 1/10

---

### 6️⃣ (C)

F(3) = P(X ≤ 3) = (1+2+3)/10 = 6/10 = 0.6

---

### 7️⃣ (C)

E(X) = 0×0.1 + 1×0.3 + 2×0.4 + 3×0.2 = 1.7

---

### 8️⃣ (B)

E(X²) = 0 + 0.3 + 1.6 + 1.8 = 3.7
Var(X) = 3.7 − (1.7)² = 0.81

---

### 9️⃣ (B)

Binomial probability:
C(6,4) × 0.7⁴ × 0.3² ≈ 0.324

---

### 🔟 (B)

Poisson probability:
(4³ × e⁻⁴) / 3! ≈ 0.195

---

### 1️⃣1️⃣ (B)

Variance = 25 → standard deviation = √25 = 5

---

### 1️⃣2️⃣ (B)

Z = (125 − 120) / 5 = 1
So P(X < 125) = P(Z < 1)

---

### 1️⃣3️⃣ (B)

Law of Large Numbers:
Sample mean converges to μ

---

### 1️⃣4️⃣ (A)

Central Limit Theorem:
Standardized sample mean → N(0,1)
