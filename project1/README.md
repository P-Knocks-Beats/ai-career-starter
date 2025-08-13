# Project 1 — Clinic FAQ Copilot
**Goal:** Answer common clinic questions from a small knowledge base.

## Plan
- Collect 10–20 FAQs into a single doc.
- Build a simple interface (notebook or form) that queries the doc via an LLM.
- Record a 3-min Loom demo.

## Test set
- 10 questions with expected answers.

## Limits & handoff
- List cases that must escalate to a human; add a short checklist.
**Goal:** Answer common clinic questions from a small knowledge base.

## Files
- `clinic_faqs.csv` — source FAQ pairs.
- `test_questions.csv` — 10 questions + expected answer points.

## How this “copilot” works (simple version)
1. Start with the FAQ CSV as your knowledge base.
2. Try answering each item in `test_questions.csv` using only that knowledge.
3. Note where the answer is missing or unclear → add/clarify rows in `clinic_faqs.csv`.

## Limits & human handoff
- Emergencies → **call 911/ER** (never give medical advice).
- If the question isn’t in the FAQ or needs a clinician, escalate to staff.

## Evidence to show in the Loom
- A quick walkthrough of the two CSVs.
- 3 examples where the FAQ answered perfectly.
- 2 examples where you *had* to escalate or add an FAQ row (explain why).
