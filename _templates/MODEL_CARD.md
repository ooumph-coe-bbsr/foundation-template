# Model / System Card

A short, honest summary of what you built — what it does, what data it used, how well it works, where it fails, and whether it's safe to use. Pair this with [`VALIDATION.md`](VALIDATION.md), which shows *how* the numbers were measured.

---

## Model Details

| Field | Detail |
|---|---|
| **Model name** | `<e.g. Leaf Disease Classifier v1>` |
| **Developer** | `<Name>`, Roll `<Roll>` |
| **Branch / Domain** | `<e.g. Civil — crack detection / Mechanical — fault sound>` |
| **Date** | `<YYYY-MM-DD>` |
| **Type** | `<e.g. Image classification / Regression / Clustering>` |
| **Tool / Framework** | `<e.g. Teachable Machine, Hugging Face, scikit-learn, Keras, Edge Impulse>` |
| **Version** | `v1.0` |

---

## Intended Use

- **Primary use:** `<what is this model designed to do?>`
- **Intended users:** `<who would use this?>`
- **Out-of-scope uses:** `<what should this NOT be used for?>`

> This is a **learning prototype** built during the Foundation Programme. It is **not certified for real-world deployment** without further testing and validation.

---

## Training / Input Data

| Item | Detail |
|---|---|
| Source | `<dataset name, URL, or "self-collected">` |
| Size | `<e.g. 500 images across 3 classes>` |
| Split | `<Train / Val / Test ratio — or "tool handled it" for no-code>` |
| Preprocessing | `<resize, augmentation, normalisation — or "none">` |
| Licence | `<CC-BY, MIT, public-government, self-collected, etc.>` |
| Personal data | `<None / or describe any personal data and how consent was handled>` |

---

## Performance

Fill in **whatever your tool reports — accuracy is the minimum.** Leave the rest blank if your (no-code) tool doesn't show them. Attach a **confusion-matrix screenshot to `assets/`** if available. See [`VALIDATION.md`](VALIDATION.md) for how these were measured and the 3-Source check.

| Metric | Value |
|---|---|
| **Accuracy** *(required)* | `___` |
| Precision *(optional)* | `___` |
| Recall *(optional)* | `___` |
| F1 Score *(optional)* | `___` |
| Other | `___` |

### Per-class performance *(optional)*

| Class | Metric | Value |
|---|---|---|
| `<Class A>` | Accuracy | `___` |
| `<Class B>` | Accuracy | `___` |

---

## Limitations

- `<Known failure cases — when does it get things wrong?>`
- `<Data gaps — e.g. only daytime images, only one crop variety, small dataset>`
- `<Bias risks — who or what might it work worse for?>`
- This prototype has **not** been validated for production use.

---

## Responsible-AI Checklist

Tick every box before submission. This is reviewed at your defence.

- [ ] **No facial recognition or biometric identification** is used (programme rule — MoU §9).
- [ ] Any images, video, or personal data were collected **with consent**, and that consent is stored.
- [ ] Data is handled in a **DPDP-compliant** way (no sharing of personal data without basis).
- [ ] I checked for **obvious bias** and considered **who could be harmed** if this were misused.
- [ ] I understand this is a **learning prototype, not a certified product.**

---

## How to Run / Try It

**Live demo / link:** `<Teachable Machine link / Hugging Face Space URL / deployed app — or "runs locally">`

**Steps to try it:**
1. `<step 1 — e.g. open the link above>`
2. `<step 2 — e.g. upload an image / enter input>`
3. `<step 3 — what to expect>`

**Code (only if your model is code-based — skip for no-code):**

```python
# Example inference code or run instructions
```

---

## Citation

Cite anything you built on:
- **Dataset(s):** `<e.g. data.gov.in, AI4Bharat, Kaggle India, ISRO Bhuvan — name + URL>`
- **Base model (if any):** `<e.g. Teachable Machine, MobileNetV2, a Hugging Face model>`

---

<sub>Model-card format adapted from Mitchell et al. 2019, *Model Cards for Model Reporting* (arXiv:1810.03993). This card is a learning exercise — it trains you to think about what you build: who it affects, where it fails, and whether it should be deployed.</sub>