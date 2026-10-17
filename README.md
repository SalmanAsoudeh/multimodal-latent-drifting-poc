# Multimodal Latent Drifting PoC

A lightweight PyTorch implementation exploring **DDIM Inversion** and **Latent Drifting** for medical image counterfactual generation (inspired by CVPR 2025 research in medical diffusion models).

## Features
- Mini-UNet architecture for educational & testing purposes.
- Deterministic DDIM Inversion ($x_0 \to x_T$).
- Latent Drift Injection ($\delta$) during reverse sampling to synthesize counterfactual progression.
- Difference Map visualization for clinical biomarker effect analysis.

## Usage
Run the script directly in any Python/Jupyter environment:
```bash
python latent_drift_poc.py
