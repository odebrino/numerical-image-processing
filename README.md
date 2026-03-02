# Numerical Image Processing - ENSTA Practice Repository

Public training repository for image processing practical sessions (TE01, TE02, TE03),
organized as hands-on Jupyter notebooks with **no final solutions**.

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
|   `-- 03_te03_segmentation_thresholding.ipynb
|-- data/
|   |-- te01/
|   |-- te02/
|   `-- te03/
|-- docs/
|   `-- study_plan.md
|-- outputs/
|   |-- te01/
|   |-- te02/
|   `-- te03/
`-- archive/
    |-- scripts_originais/
    |-- generated_outputs/
    `-- professor_pdfs/
```

## Why Professor PDFs Are Not in the Public Repo

Original course statement PDFs are stored locally in `archive/professor_pdfs/` and ignored by git,
so they can be removed before/after publishing as needed.

All essential task information has been rewritten in English directly into the notebooks.

## Quick Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name numerical-image-processing
jupyter lab
```

## Workflow
1. Open notebooks in order:
   - `01_te01_fundamentals_fft.ipynb`
   - `02_te02_contrast_noise_video.ipynb`
   - `03_te03_segmentation_thresholding.ipynb`
2. Implement every `TODO` cell.
3. Write interpretations in markdown answer sections.
4. Save generated artifacts under `outputs/teXX/`.

## Public Repository Notes
- `.venv/`, IDE settings, archived local materials, and generated outputs are ignored.
- Notebooks intentionally keep structure/prompts only, without complete answers.
