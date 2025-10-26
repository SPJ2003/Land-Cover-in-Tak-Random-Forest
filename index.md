# Tak Land Cover — Random Forest (Lab 6)

Static site for **Land Cover Classification (Tak Province)** using a Random Forest model.

## 🚀 Quick start (GitHub Pages)

1. Create a new repo (e.g., `Tak-RF-Lab6`) and push these files.
2. Go to **Settings → Pages** and set
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`), folder `/ (root)`
3. Open: `https://<your-username>.github.io/Tak-RF-Lab6/`

> All images are under `assets/` and the site is 100% static (no build needed).

## 📁 Structure
```
Tak-RF-Lab6/
├── index.html
├── README.md
└── assets/
    ├── tak_map.png
    ├── confusion_matrix.png
    ├── accuracy_chart.png
    └── feature_importance.png
```

## 🧠 About
- Satellite: Sentinel‑2 Surface Reflectance
- Indices: NDVI, NDWI
- Training samples: ESA WorldCover (2 classes: Forest/Agriculture)
- Model: Random Forest (~200 trees), trained/evaluated in GEE
- Metrics: OA ≈ 94.7%, Kappa ≈ 0.89, UA/PA per class

© 2025-10-26 • Supannika Jitjak
