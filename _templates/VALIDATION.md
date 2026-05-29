# Validation Report

**Project:** `<title>` · **Student:** `<Name>` (`<Roll>`) · **Module:** `<m01–m06>` · **Date:** `<YYYY-MM-DD>`

How I tested this deliverable and confirmed the result is real. Complete one of these for **every module**. If your deliverable is a trained model, also fill in [`MODEL_CARD.md`](MODEL_CARD.md) for the model-specific detail.

---

## 1. Objective

`<What does this deliverable do? What problem does it solve? 2–3 sentences.>`

---

## 2. Data / Input

| Item | Detail |
|---|---|
| Source | `<where did the data come from? name + URL, or "self-collected">` |
| Size | `<rows × columns, or number of files>` |
| Preprocessing | `<cleaning / formatting steps applied — or "none">` |
| Consent / Licence | `<openly licensed? any personal data? if images/video of people: consent collected and stored>` |

---

## 3. Method

`<Describe the approach — algorithm, tool, no-code platform, or automation steps. Enough that someone could repeat it.>`

---

## 4. Results

| Item | Value |
|---|---|
| **Main result / metric** | `<accuracy, F1, RMSE, % correct, time saved, error count — whatever fits your deliverable>` |
| Baseline comparison | `<vs. doing it manually, a simple guess, or a previous version>` |
| Edge cases tested | `<unusual inputs you tried and what happened>` |

> Put screenshots, confusion matrices, or sample outputs in `assets/` and reference them here. Test on inputs the tool has **not** seen before — not your training data.

---

## 5. The 3-Source Rule Check

Before trusting an important output, confirm it against **three independent checks**:
1. **Reference / documentation** — a textbook, dataset label, or trusted source.
2. **A second independent source** — a different tool, dataset, or a person who knows the domain.
3. **Logic or a real re-test** — does it hold up against physical reality when you check?

If the three disagree, the output is suspect — investigate before relying on it.

| Claim / output to check | Source 1 — reference / docs | Source 2 — independent source | Source 3 — logic / real re-test | Verdict |
|---|---|---|---|---|
| `<e.g. "model labels this leaf as diseased">` | `<textbook / dataset label>` | `<asked a second tool or an expert>` | `<checked the actual leaf>` | `<Confirmed / Corrected>` |
|  |  |  |  |  |

---

## 6. Limitations & Failure Modes

- `<What doesn't work? When does it get things wrong?>`
- `<Where would this fail outside the test conditions (production)?>`
- `<Any bias concerns — who or what does it work worse for?>`
- **I would NOT trust this for:** `<inputs or conditions it was never tested on>`

_(If you built a model, the full limitations are also recorded in [`MODEL_CARD.md`](MODEL_CARD.md).)_

---

## 7. AI Tool Usage Summary

Brief summary for this module — full log in [`AI_USAGE.md`](../AI_USAGE.md).

| Tool | Used for | Verified how? |
|---|---|---|
| `<e.g. ChatGPT>` | `<debugging pandas code>` | `<ran the code, confirmed the output>` |
|  |  |  |

---

## 8. Defence Readiness Checklist

- [ ] I can explain every step / line of my work.
- [ ] I can reproduce the result live.
- [ ] I tested on data the tool had **not** seen before.
- [ ] I have documented limitations honestly.
- [ ] My `AI_USAGE.md` is up to date.
- [ ] My `prompt-log.md` shows my key prompts **and how I improved them**.
- [ ] **No facial recognition used**, and consent was collected for any personal data (DPDP).

---

> **Trainer sign-off:** `<trainer name>` · **Date:** `<YYYY-MM-DD>` — or recorded via the trainer's review on this repository.