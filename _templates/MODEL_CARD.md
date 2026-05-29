# Model Card

_Based on [Mitchell et al. 2019 — Model Cards for Model Reporting](https://arxiv.org/abs/1810.03993)_

---

## Model Details

| Field | Detail |
|---|---|
| **Model name** | _e.g. Leaf Disease Classifier v1_ |
| **Developer** | <Name>, Roll <Roll> |
| **Date** | YYYY-MM-DD |
| **Type** | _e.g. Image classification (CNN) / Regression / Clustering_ |
| **Framework** | _e.g. Keras, scikit-learn, Teachable Machine, Edge Impulse_ |
| **Version** | _v1.0_ |

## Intended Use

- **Primary use:** _What is this model designed to do?_
- **Intended users:** _Who would use this?_
- **Out-of-scope uses:** _What should this NOT be used for?_

## Training Data

| Item | Detail |
|---|---|
| Source | _Dataset name, URL, or "self-collected"_ |
| Size | _e.g. 500 images, 3 classes_ |
| Split | _Train / Val / Test ratio_ |
| Preprocessing | _Resize, augmentation, normalisation steps_ |
| Licence | _CC-BY, MIT, proprietary, etc._ |
| PII | _Does the data contain personal information? If yes, how is it handled?_ |

## Performance

| Metric | Value |
|---|---|
| Accuracy | ___ |
| Precision | ___ |
| Recall | ___ |
| F1 Score | ___ |
| Other | ___ |

### Performance by subgroup (if applicable)

| Subgroup | Metric | Value |
|---|---|---|
| _e.g. Class A_ | _Accuracy_ | ___ |
| _e.g. Class B_ | _Accuracy_ | ___ |

## Limitations

- _Known failure cases_
- _Data gaps (e.g. only daytime images, only one crop variety)_
- _Bias risks_

## Ethical Considerations

- _Any potential for harm or misuse?_
- _Privacy implications?_
- _Consent obtained for data collection?_
- _Compliant with DPDP Act?_

## How to Use

```python
# Example inference code or instructions
```

## Citation

_If you used someone else's model or dataset, cite it here._

---

> **Note:** This model card is a learning exercise. It trains you to think critically
> about what you build — who it affects, where it fails, and whether it should be deployed.
