# Design Decisions

This document explains reasoning behind major architectural choices.

---

## 1. Mode-Based Separation

Decision:
Separate learning into distinct aspects.

Reason:
Different cognitive states require different response structures.

Result:
Improved clarity and reduced instructional blending.

---

## 2. Independent Question Processing

Decision:
No conversational carryover between questions.

Reason:
Prevent hidden state dependency and maintain exam-relevant clarity.

Result:
Predictable and controlled system behavior.

---

## 3. Authentication Strategy

Learn Mode:
Soft gate after limited usage.

Doubt & Teach-Back:
Strict authentication required.

Reason:
Encourage exploration while protecting deeper engagement and logging.

---

## 4. Teach-Back Verification

Decision:
Allow users to explain concepts in their own words.

Reason:
Articulation exposes logical gaps better than passive reading.

Result:
Shift from answer consumption to understanding validation.

---

## 5. Cognitive Load Reduction (v2.1)

Decision:
Refine descriptions, remove redundant explanations, standardize navigation.

Reason:
Reduce noise and increase intentional interaction flow.

Result:
Cleaner learning transitions.
