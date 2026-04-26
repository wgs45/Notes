# 📘 **Assignment 1**

## **Week 1 Assignment: Fundamentals of Probability and Set Operations**

**Topic: Electronic Product Quality Inspection Analysis**

Suppose an electronics factory conducts quality inspections on the smartphones it produces. We randomly select one phone for inspection and define the following two events:

- **Event A**: The phone’s _screen_ has defects.
- **Event B**: The phone’s _battery_ has defects.

Please answer the following questions based on the concepts of set theory and uncertainty mentioned in the textbook:

---

### **1. Symbol Representation**

Use set operation symbols **( ∪ , ∩ , ^c , \ )** to represent the following events:

(a) The phone has at least one defect in either the screen or the battery.

(b) The phone has defects in both the screen and the battery at the same time.

(c) The phone is completely qualified _(i.e., both the screen and battery have no defects)_.

(d) The phone has a defect only in the screen, but the battery is normal.

---

### **2. Conceptual Analysis**

If the factory manager says:
“In our manufacturing process, screen defects and battery defects are **mutually exclusive events**.”

(a) Express this statement using set notation.

(b) What does this statement mean in terms of actual product quality?
_(For example: Is it possible for a phone to have both defects at the same time?)_

---

# ✨ **Answers + Step-by-Step Explanation**

## 🌸 **1. Symbol Representation**

Let’s interpret each carefully:

---

### **(a) At least one defect (screen OR battery)**

👉 This is the **union** of events:

[
A ∪ B
]

💡 Meaning:

- Screen defective OR battery defective OR both
- “At least one” always means **union**

---

### **(b) Both defects (screen AND battery)**

👉 This is the **intersection**:

[
A ∩ B
]

💡 Meaning:

- Screen defective AND battery defective simultaneously

---

### **(c) Completely qualified (no defects at all)**

👉 This means **NOT A AND NOT B**

Using De Morgan’s Law:

[
(A ∪ B)^c
]

💡 Equivalent form:

[
A^c ∩ B^c
]

💡 Meaning:

- Screen is NOT defective
- Battery is NOT defective

---

### **(d) Only screen defective, battery normal**

👉 This is:

[
A ∩ B^c
]

💡 Meaning:

- Screen defective
- Battery NOT defective

---

## 🌸 **2. Conceptual Analysis**

---

### **(a) Mutually Exclusive (集合表示)**

👉 By definition:

[
A ∩ B = ∅
]

💡 Meaning:

- The intersection is empty
- They **cannot happen together**

---

### **(b) Real-world interpretation**

This statement means:

👉 A phone **cannot** have both defects at the same time.

So:

- If the screen is defective → battery must be fine
- If the battery is defective → screen must be fine

💡 In simple terms:

> “One defect excludes the possibility of the other.”

---

⚠️ But here’s a **critical insight** (this is where exams love to trick you):

In real manufacturing…

👉 This assumption is usually **unrealistic**

Because:

- A phone _can_ have multiple defects
- Screen and battery issues are typically **independent**, not mutually exclusive

So the manager’s claim is more like a **model assumption**, not reality.

---

# 🌟 **Key Takeaways (Super Important for Exams)**

- **Union ( ∪ ) → “OR / at least one”**
- **Intersection ( ∩ ) → “AND / both”**
- **Complement ( ^c ) → “NOT”**
- **Difference ( A \ B ) → “A but not B”**
- **Mutually Exclusive → Intersection = ∅**
