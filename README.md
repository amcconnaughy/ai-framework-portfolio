# AI Evaluation & Prompt Quality Portfolio

> Non-coding portfolio focused on AI governance: how to define quality, design prompts that reliably meet it, and verify results with ground truth and test cases. All examples are synthetic; no real user data.

---

## Overview

This repo presents a practical, evaluator-first approach to AI quality:
- a weighted scoring framework,
- prompt design principles aligned to that framework,
- ground-truth reference answers with acceptance bars,
- and scored test cases that exercise decision bands and release gates.

No tooling or code is required—just clear standards and repeatable review.

---

## Structure

**01-evaluation-frameworks**  
- **evaluation-framework**: 0–2 rubric with weighted criteria (Accuracy ×3, Safety & Compliance ×3, plus four 1× dimensions), decision bands, structure caps, high-stakes thresholds, and N/A rescaling.

**02-prompt-engineering**  
- **prompt-design-principles**: practical guidance for prompts that are safe, scannable, and easy to score.  
- **prompt-examples**: before/after pairs aligned to the rubric.

**03-ground-truth-guidance**  
- **ground-truth-framework-and-examples**: copy-ready reference answers with acceptance bars and scoring notes for calibration and testing.

**04-test-cases**  
- **test-framework-and-examples**: scored cards illustrating Auto-Approve, Human Review, Regenerate, and Reject decisions, including structure-cap enforcement.

---

## How to Use

1. **Set standards:** Start with **01-evaluation-frameworks** to align on scoring and decision bands.  
2. **Design prompts:** Use **02-prompt-engineering** to generate outputs that map cleanly to the rubric.  
3. **Calibrate & test:** Pair **03-ground-truth-guidance** (reference answers + acceptance bars) with **04-test-cases** (scored cards).  
4. **Enforce gates:** Apply **blockers**, **structure caps**, and **N/A rescale** exactly as written.

---

## Note

All artifacts are for demonstration and calibration.  
No real user data, names, emails, or records are included.
