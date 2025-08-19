## Code
**Prediction model**
- The dataset [`data_office_1.csv`](data_office_1.csv) is provided as a sample dataset. It can be used both for testing and for training the prediction model.
- A pre-trained AutoGluon-Tabular model is available for download: [Google Drive link](https://drive.google.com/drive/folders/1KXjiYUaeBUwdGpdn4ECwri-P5tG1W-wa?usp=sharing).  
- Alternatively, the code [`1_ML_AutoGluon.ipynb`](1_ML_AutoGluon.ipynb) can be used to train the prediction model.  

**Optimization (Main)**
- The main optimization workflow for flexible building space usage is implemented in [`2_Flexible_wall.ipynb`](2_Flexible_wall.ipynb).  

---

## Notes
**File paths**  
- Some paths inside the notebooks may need to be updated depending on your local directory structure.  

**Library**  
- The project relies on the [pythermalcomfort](https://pythermalcomfort.readthedocs.io/) library. Since APIs may change across versions, please refer to the official documentation if you encounter issues.

---

## Paper
- Title: [A data-driven multi-objective optimisation framework for energy efficiency and thermal comfort in flexible building spaces](https://www.sciencedirect.com/science/article/pii/S0378778825008308)
- This paper proposes the first data-driven multi-objective optimisation framework that allows walls to be moved to the best places for optimal energy efficiency and thermal comfort. It leverages surrogate machine learning models for room-level energy prediction and Multi-objective Evolutionary Algorithms (MOEAs) enhanced with a wall-reordering mutation strategy to balance between energy usage and thermal feelings of occupants.
