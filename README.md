# mlops-ml-project (baseline)

## Installation

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

## Entraînement

```bash
python scripts/train.py
```

## Évaluation

```bash
python scripts/evaluate.py
```

## Artefacts générés

- artifacts/model.joblib
- artifacts/metrics.json
- artifacts/confusion_matrix.png
- artifacts/report.json