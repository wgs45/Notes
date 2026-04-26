# 📘 **Assignment 2**

A research lab has **5 PhD students (A, B, C, D, E)** and **3 Master’s students (F, G, H)**.

1. From these 8 people, choose 3 people to form an oral examination committee.
   → How many different combinations are there?

2. If it is required that the committee must include **at least 1 PhD student**, how many possible selections are there?

3. From the 8 people, randomly choose 3 people.
   → Find the probability that the selection contains **exactly 2 PhD students and 1 Master’s student**.
   _(Use the classical probability approach)_

---

# ✨ **Solutions + Step-by-Step Explanation**

## 🌸 **Important Idea First (Combination Basics)**

We are choosing people **without order**, so we use combinations:

> “Choose k people from n people”

Formula idea: nCk (you don’t need to write it formally, just understand the logic)

---

## 🌸 **1. Total number of ways to choose 3 from 8**

We choose any 3 people out of 8:

- 8C3 = (8 × 7 × 6) / (3 × 2 × 1)
- = 56

✅ **Answer: 56 ways**

---

## 🌸 **2. At least 1 PhD student**

This is a classic trick 💡

Instead of counting directly, we use:

> At least 1 PhD = Total − (No PhD at all)

---

### Step 1: Total ways

= 56 (from Q1)

---

### Step 2: No PhD (all 3 are Master’s)

We only have 3 Master’s students (F, G, H), so:

- Choose all 3 → 3C3 = 1

---

### Step 3: Subtract

- 56 − 1 = 55

✅ **Answer: 55 ways**

---

## 🌸 **3. Probability of exactly 2 PhDs and 1 Master’s**

We use **classical probability**:

> Probability = (favorable outcomes) / (total outcomes)

---

### Step 1: Total outcomes

From Q1:
= 56

---

### Step 2: Favorable outcomes

We want:

- 2 PhDs from 5 → 5C2 = (5 × 4) / 2 = 10
- 1 Master’s from 3 → 3C1 = 3

Multiply:

- 10 × 3 = 30

---

### Step 3: Probability

- 30 / 56 = 15 / 28

---

✅ **Final Answer: 15/28 ≈ 0.536**

---

# 🌟 **Key Takeaways (Exam Gold 💎)**

- “Choose” → use combinations (order doesn’t matter)
- “At least” → often use **complement method**
- Probability = favorable / total
- When selecting from different groups → **multiply combinations**
