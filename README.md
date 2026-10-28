# MRCP1

**A personal, evidence-aware study workspace for MRCP(UK) Part 1.**

This repository will hold original study notes, clinical reasoning prompts, question-performance logs, and spaced-recall plans. The aim is to learn medicine well enough to answer unfamiliar MRCP questions, rather than just memorise lists.

> **Status:** Initial setup. The study system described below is a plan, not a claim that the files, quizzes, or dashboard already exist.
>
> **Exam target:** January 2027 (provisional; registration and exact sitting to be confirmed).

## Study method: C — Hybrid

For each topic, use one repeatable loop:

1. **Baseline:** Answer 5–10 single-best-answer questions *before* reading, to find gaps.
2. **Focused learning:** Read the relevant textbook pages and work through the underlying mechanisms, clinical features, investigations, and management.
3. **Apply:** Answer 10–20 fresh MRCP-style best-of-five questions, ideally one at a time, with clear reasoning for both correct and incorrect options.
4. **Diagnose errors:** Record knowledge gaps, misread stems, weak discrimination between options, and time-pressure errors.
5. **Recall:** Re-test weak points after roughly **1, 3, 7, and 21 days**; adjust intervals to performance.
6. **Integrate:** Move from topic-specific questions to mixed, timed sets and full mock papers.

**Rule:** If the baseline shows strong knowledge, move quickly to harder questions. If the score is low, teach the mechanism before increasing question volume.

## References and evidence rules

- **Core textbook:** *Step Up to MRCP*, 3rd edition (held privately; **not stored in this repository**).
- **Exam specification:** The official MRCP(UK) Part 1 blueprint, format, and published exam information.
- **Changing clinical guidance:** Check current UK sources such as NICE, the British National Formulary (BNF), NHS guidance, and the relevant professional society.
- **Question banks:** Use legally accessed questions; record only original reflections, topic tags, results, and links where terms permit.

Each note or answer should mark the basis of a claim:

| Label | Meaning |
| --- | --- |
| `BOOK` | Paraphrase tied to the textbook edition and exact page |
| `GUIDELINE` | Current clinical advice with source and access/check date |
| `EXAM` | Exam technique, blueprint detail, or an exam-focused inference |
| `UNCERTAIN` | A point to verify; do not present it as settled |

For book citations, distinguish **PDF page number** from **printed book page number**. Keep both when known. If textbook advice and current guidance differ, **show the difference explicitly** rather than silently replacing the book.

## Planned workspace

The following directories are **proposed**, not yet created:

```text
MRCP1/
├── README.md                  # Purpose, method, and working rules
├── roadmap/                   # Topic list and exam priorities
├── notes/                     # Original, sourced topic summaries
├── questions/                 # Original practice items and reasoning
├── errors/                    # Wrong-answer and uncertainty log
├── reviews/                   # Spaced recall prompts and review dates
└── progress/                  # Session scores, timing, and trends
```

A session entry should track:

```text
Date:
Specialty / topic:
Book pages (PDF / printed):
Baseline: correct / total
Practice: correct / total
Time per question:
Errors: concept | reasoning | stem reading | time
Key takeaways:
Sources checked and dates:
Next review: +1d / +3d / +7d / +21d
```

**Progress measures:** performance by specialty, accuracy on first attempt, repeat-error rate, time per question, and timed mixed-set results. A high score on repeated questions does not by itself prove readiness.

## Starting point

**Session 001 — Cardiology: introductory cardiovascular physiology**

- First use the textbook's opening Cardiology pages (initial PDF reference: pages 31–37; verify page labels when indexing).
- Run a short diagnostic quiz.
- Teach only the missed or weak concepts, with links to the relevant pages.
- Finish with fresh best-of-five questions and a small error log.
- Book the first spaced-recall review based on the result.

## Near-term roadmap

- [ ] Confirm the exact exam date and booking.
- [ ] Index the textbook's actual chapter headings and PDF/print page mapping.
- [ ] Build one reusable session template and error-log format.
- [ ] Complete and review the first Cardiology session.
- [ ] Add a specialty-level plan based on the current MRCP(UK) blueprint.
- [ ] Start mixed timed blocks once enough topics have been covered.
- [ ] Add a simple progress dashboard **only after** useful session data exists.

## Copyright, privacy, and safety

**Do not commit the textbook PDF, bulk OCR output, long book extracts, copied paid-bank questions, patient-identifiable data, passwords, or API keys.** This repository may be public; keep copyrighted source material in private, licensed storage. Write notes in your own words, cite sources, and use only original or licensed questions.

This is an **exam-preparation workspace**, not a clinical decision-support system. Verify drug doses, contraindications, diagnostic thresholds, and clinical pathways against current primary guidance before use in patient care.
