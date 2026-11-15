# Crop Row Navigator

My Agricultural Engineering and AI/ML challenge.

## Agricultural problem
A robot travelling between crop rows needs to stay near the centre
of the path to reduce the risk of damaging crops.

## Project goal
Mark crop rows in a clear farm image and estimate the horizontal
offset of a simulated robot from the centre of the path.

## Planned deliverable
A beginner-friendly Python project with an annotated image,
an offset estimate and reproducible instructions.

## Scope and limitations
- Begin with one clear image and a simple image-processing baseline.
- Report the offset in pixels.
- Converting pixels to real-world distance requires calibration.
- This is an image-based demonstration, not a robot control system.

## Current progress
- Created a local Git repository with a main branch.
- Connected the repository to GitHub and pushed initial documentation.
- Added and pushed .gitignore rules.
- Created and verified a Python 3.14.0 virtual environment.
- Created data/raw, src and results folders.
- Documented local environment setup and project structure.
- Dataset selection and implementation have not started.

## Local setup

Development started on Windows 11 using Python 3.14.0.

From the repository folder, create a virtual environment:

```powershell
python -m venv .env
```

Activate it in PowerShell:

```powershell
.\.env\Scripts\Activate.ps1
```

The environment folder is excluded from Git.

## Project structure

- `data/raw/`: original input images; excluded from Git.
- `src/`: Python source code.
- `results/`: generated images and measurements.

Empty folders are not tracked by Git.