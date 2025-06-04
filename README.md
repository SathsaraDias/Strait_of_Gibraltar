```markdown
# Strait of Gibraltar: 3D Ocean Simulation Data

![Strait of Gibraltar Simulation](featured.gif)

[![Paper DOI](https://img.shields.io/badge/arXiv-2311.01377-blue)](https://arxiv.org/abs/2311.01377)

_Accompanies:_  
**Dias, L. et al., “Analysis of tidal flows through the Strait of Gibraltar using Dynamic Mode Decomposition”  
[arXiv:2311.01377](https://arxiv.org/abs/2311.01377) (2023)_

---

## 🌊 At a Glance

- **3D numerical simulation** of ocean currents in the Strait of Gibraltar (MITgcm)
- Hourly snapshots (144), 6-day time span
- Fields: Zonal (U), Meridional (V), and Vertical (W) velocities, on a regular grid
- **Key phenomena:** tidal flows, ocean gyres, internal gravity waves
- **Data format:** MATLAB `.mat`
- **Used in:** [Dynamic Mode Decomposition (DMD)](https://en.wikipedia.org/wiki/Dynamic_mode_decomposition) analysis for peer-reviewed publication

---

## 🚀 Quick Start: Download Data with Git LFS

If you only want the `.mat` data file(s) and are new to Git or Git LFS, **follow these steps**:

### 1. Install Git LFS

- **Windows:**  
  Download and run the [Git LFS installer](https://git-lfs.github.com/), then open “Git Bash” or “Command Prompt” and run:
```

git lfs install

```
- **macOS:**  
```

brew install git-lfs
git lfs install

```
- **Linux (Debian/Ubuntu):**  
```

sudo apt-get install git-lfs
git lfs install

````
For other distros, see [Git LFS install guide](https://github.com/git-lfs/git-lfs/wiki/Installation).

### 2. Clone and Download the Full Dataset

```bash
git clone https://github.com/<your-username>/Strait_of_Gibraltar.git
cd Strait_of_Gibraltar
git lfs pull
````

*Replace `<your-username>` with your GitHub username if needed.*

### Already Cloned but See Only a Tiny `.mat` File?

Just run:

```bash
git lfs pull
```

from inside your repository folder.

---

## 📖 Reference

If you use this dataset or code, please cite our paper:

> Dias, L. et al. (2023).
> *Analysis of tidal flows through the Strait of Gibraltar using Dynamic Mode Decomposition*.
> [arXiv:2311.01377](https://arxiv.org/abs/2311.01377)

---

## 📬 Questions or Problems?

* Open an [Issue](https://github.com/<your-username>/Strait_of_Gibraltar/issues) on this repository
* Or email the corresponding author (see the paper)

---

*Thank you for your interest! This repository aims to support open, reproducible research in oceanography and data-driven fluid dynamics.*

```

---

**What to do next:**
- Replace `<your-username>` with your GitHub username or organization.
- Upload your `featured.gif` to the repo (same directory as this README.md).

**This version is robust for all markdown/YAML parsers and ready for any professional audience.**
```
