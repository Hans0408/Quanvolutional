# Quanvolutional Experiments

A compact research repository for experimenting with **quanvolutional neural networks** (quantum-inspired/quantum-assisted convolutional feature extraction) using PyTorch and PennyLane.

> Current implementation is notebook-first: all experiments live in `Experiments.ipynb`.

## Project Goals

- Compare classical and hybrid quantum-classical image pipelines.
- Prototype patch-based quanvolutional transforms.
- Measure training behavior and model quality under different experimental settings.

## Repository Structure

```text
.
├── Experiments.ipynb        # Main experiment notebook
├── README.md                # Project overview and usage
├── requirements.txt         # Python dependencies for local runs
├── pyproject.toml           # Tooling configuration (lint/format checks)
├── CONTRIBUTING.md          # Contribution workflow and quality standards
└── .gitignore               # Common Python/Jupyter ignores
```

## Quick Start

### 1) Create and activate a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

### 2) Install dependencies

```bash
pip install -r requirements.txt
```

### 3) Launch Jupyter

```bash
jupyter notebook
```

Open `Experiments.ipynb` and run cells in order.

## Reproducibility Notes

- Use fixed random seeds where possible for fair comparisons.
- Prefer running the notebook top-to-bottom in a fresh kernel.
- Record experiment parameters/results in markdown cells next to outputs.

