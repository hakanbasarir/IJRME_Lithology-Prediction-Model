# Lithology Prediction using MWD Data & XGBoost

> **Paper**: Akyildiz, O., Basarir, H., & Ellefmo, S. L. (2024).  
> *The development of a lithology prediction model using measurement while drilling data in a quartzite quarry*.  
> **International Journal of Mining, Reclamation and Environment**, 39, 93–109.  
> 🔗 [Open Access Paper](https://www.tandfonline.com/doi/full/10.1080/17480930.2024.2362577)  
> 📄 DOI: [10.1080/17480930.2024.2362577](https://doi.org/10.1080/17480930.2024.2362577)

---

## Abstract

The paper outlines the development of an XGBOOST algorithm-based lithology prediction model using MWD data from blast hole drilling machines in a quartzite mine. The focus is on predicting shale layers to address quartzite quality issues caused by shale dilution. Initial data from 10 boreholes were used to construct a small database, progressively expanded with field observations and historical records then the best-performing model was selected. Sensitivity analysis identified key MWD parameters impacting the model, emphasising those with distinct characteristics on the lithologies. Overall, the XGBOOST algorithm proved effective, supporting the mine's strategic goals for digital transformation and sustainable resource use.

---

## Requirements & Installation

This code was developed and tested with:
- Python 3.8+
- Core libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`, `joblib`, `openpyxl`

```bash
# Clone the repository
git clone https://github.com/hakanbasarir/IJRME_Lithology-Prediction-Model
cd lithology-prediction-xgboost

# Install dependencies
pip install -r requirements.txt
