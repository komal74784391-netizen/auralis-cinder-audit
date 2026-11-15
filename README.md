# Cinder

Official implementation of **Cinder: Auditing Training Data Provenance at Scale**.

## Installation

```bash
pip install -r requirements.txt
```

## Repository structure

```
src/audit.py
src/provenance.py
run_audit.py
requirements.txt
```

## Training

Run `python train.py --config configs/default.yaml` to reproduce the main results.
Checkpoints and logs are written to `runs/`.

## Evaluation

Run `python eval.py --checkpoint runs/latest` to reproduce the benchmark tables.

## Citation

```bibtex
@inproceedings{misc,
  title = {Cinder: Auditing Training Data Provenance at Scale},
  booktitle = {Proceedings of the corresponding venue},
  year = {2025}
}
```
