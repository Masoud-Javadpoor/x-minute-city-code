<h1 align="center">x-minute-city-code</h1>

# 1. Overview
Code and notebook to extract POIs from OpenStreetMap (Overpass API) and export category-specific Shapefiles for x-minute city analysis.

# 2. Installation
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

# 3. How to run
Open and run `notebooks/POIs_Category.ipynb` from the repository root.

# 4. Folder structure
- **data/**: Input data (add your study-area mask Shapefile here).
- **notebooks/**: Jupyter notebooks (main workflow).
- **outputs/**: Generated Shapefiles (not tracked in git).

# 5. Before You Upload

See [CHECKLIST.md](CHECKLIST.md) for the step-by-step pre-upload guide (Mask files, placeholders, GitHub Release, Zenodo DOI).

# 6. Citation
If you use this code, please cite the associated paper:
- **[Paper Title]** (Nature Communications, 2026)
- **[Your Name]**, **[Co-authors]**
- Code: `https://github.com/[Your GitHub Username]/x-minute-city-code`
- DOI: (add Zenodo DOI after release)

