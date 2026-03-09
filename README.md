# Numerical Image Processing - ENSTA Practice Repository

Public training repository for image processing practical sessions.

## Goals
- Practice image processing workflows using OpenCV, NumPy, and Matplotlib.
- Keep exercises reproducible and GitHub-ready.
- Separate datasets, notebooks, outputs, and archived local material.

## Repository Structure

```text
.
|-- notebooks/
|   |-- 01_te01_fundamentals_fft.ipynb
|   |-- 02_te02_contrast_noise_video.ipynb
|   |-- 03_te03_segmentation_thresholding.ipynb
|   `-- 04_te04_morphology_connected_components.ipynb
|-- data/
|   |-- te01/
|   |-- te02/
|   |-- te03/
|   `-- te04/
|-- outputs/
|   |-- te01/
|   |-- te02/
|   |-- te03/
|   `-- te04/
```
## Quick Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name numerical-image-processing
jupyter lab
```

## Public Repository Notes
- `.venv/`, IDE settings, archived local materials, and generated outputs are ignored.
- Notebooks intentionally keep structure/prompts only, without complete answers.
