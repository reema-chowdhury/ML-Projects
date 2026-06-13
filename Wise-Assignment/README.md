# Wise Analytics Case Study

Two-part, async submission (no live presentation). Deliver:
1. An analysis report/deck (Word / PPT / PDF / Slides — 5–10 slides or 2–3 pages)
2. The supporting notebook/code showing how conclusions were reached

---

## Task 1 — Analysis Review (~30 min)

Act as a **mentor reviewing junior analyst Angela's work**. Angela is analysing the
**impact of speed on growth** and has produced an early view of **speed vs. conversion**.
Assume her chart reflects a *real* customer behaviour pattern — interpret, don't re-analyse.

Answer each in one concise paragraph:

- **1.1** How would she interpret these results? (What is the relationship?)
- **1.2** What conclusions can you infer from this data? (Why might it matter for growth?)
- **1.3** What would you recommend Angela and the Speed team do next? (Specific quantitative or experimental next steps.)

## Task 2 — Data Analysis (~120 min)

Explore funnel performance in the international transfer setup flow:

> **1. Transfer Created → 2. Transfer Funded → 3. Transfer Transferred**

Use the event-level dataset (`wise_funnel_events`), which includes **customer region,
platform, and experience level (new vs. existing)**. SQL or Python both fine.
No deep data-quality checks needed — assume the data is reliable; treat anything odd as an
**analytical insight**, not a tracking error.

Answer:

- **2.1** What conversion trends do you observe? What may be driving them?
- **2.2** Are there anomalies that need product attention? What customer behaviours might be behind them?

---

## Evaluation Criteria

| Criterion | What they look for |
|---|---|
| **Structuring & Problem Solving** | Clearly define the problem and approach; focus on highest-impact analysis (80/20 thinking) |
| **Actionable Insights** | Recommendations help the product team decide what to do next |
| **Communication** | Clarity, logical structure, appropriate visualisations |
| **Code Quality** | Well-structured, readable, reproducible code |

## Helpful Tips

**General**
- Start with the **problem, not the data** — one or two sentences framing what you're solving.
- Think *"What would the product manager do with this?"* — make recommendations specific and actionable.
- **Prioritise signal over completeness** — answer the core questions well rather than exploring every angle.

**Task 1**
- Assume Angela's chart reflects real customer behaviour — avoid hand-waving.
- Focus on interpretation, not re-analysis: What is the relationship? Why might it matter for growth? What could they do next (quantitatively or experimentally)?

**Task 2**
- Reward clear segmentation: **New vs. Existing**, **Region**, **Platform**.
- Call out **where conversion drops and why** (the "so what?") — more important than complex models.
- For anomalies, propose **2–3 plausible hypotheses** rooted in customer behaviour, not tracking issues.
- Use **1–2 crisp visuals** rather than many charts.

**Code**
- Keep code blocks tidy and commented; name temporary tables logically.
- Reproduce the sequence of your thinking clearly.

## Deliverable

- A short, sharp deck or doc (**5–10 slides, or 2–3 pages**).
- Simple charts to illustrate trends — no heavy design needed.

---

## Files in this folder

- `Global Product – Product Analytics Case Study (2).pdf` — the case study brief
- `wise_funnel_events (3).csv` — the event-level funnel dataset
- `Case_Study_Analysis.ipynb` — supporting analysis notebook
