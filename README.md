# End-to-End Chest Cancer Classification using MLflow & DVC

<p align="center">
  <img src="https://img.shields.io/badge/Python-ML-blue" />
  <img src="https://img.shields.io/badge/MLflow-Experiment%20Tracking-blueviolet" />
  <img src="https://img.shields.io/badge/DVC-Data%20Versioning-orange" />
</p>

## Workflow

1. Update `config.yaml`
2. Update `secrets.yaml` (Optional)
3. Update `params.yaml`
4. Update the Entity
5. Update the Configuration Manager
6. Update the Components
7. Update the Pipeline
8. Update `main.py`
9. Update `dvc.yaml`

---

## MLflow

<p>
  <img src="https://img.shields.io/badge/MLflow-Tracking-blueviolet" />
</p>

Used for experiment tracking:
- Parameters
- Metrics
- Models

```bash
mlflow ui
```

🔗 https://mlflow.org/docs/latest/

---

## DVC

<p>
  <img src="https://img.shields.io/badge/DVC-Version%20Control-orange" />
</p>

Used for data & pipeline versioning:

```bash
dvc repro
dvc dag
```

🔗 https://dvc.org/doc

---

## Highlights

- Reproducible ML pipeline
- MLflow + DVC integrated
- Production-ready structure
