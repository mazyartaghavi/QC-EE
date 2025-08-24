# Q-CMAPO: Quantum–Classical Multi-Agent Policy Optimization (CTDE + QAOA)

**Status:** Reproducible reference implementation with end-to-end training loops integrating PennyLane + Qiskit (Aer) for QAOA-parameterized policies under CTDE. Includes classical baselines, ablation scripts, sensitivity analyses, and CI-backed smoke tests.

## Abstract
Q-CMAPO embeds parameterized quantum circuits (QAOA-style) into a CTDE training pipeline to improve exploration–exploitation in partially observable MARL. This repository provides a complete, executable implementation with configuration files, baselines, and scripts to reproduce key tables/figures, addressing concerns about quantum integration and reproducibility.

## Quickstart

### 1) Create environment
```bash
# with conda
conda env create -f environment.yml
conda activate qcmapo

# or with pip
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt



