## Code
**1. Prediction model**
- The dataset [`data_office_1.csv`](data_office_1.csv) is provided as a sample dataset. It can be used both for testing and for training the prediction model.
- A pre-trained AutoGluon-Tabular model is available for download: [Google Drive link](https://drive.google.com/drive/folders/1KXjiYUaeBUwdGpdn4ECwri-P5tG1W-wa?usp=sharing).  
- Alternatively, the code [`1_ML_AutoGluon.ipynb`](1_ML_AutoGluon.ipynb) can be used to train the prediction model.  

**2. Optimization (Main)**
- The main optimization workflow for flexible building space usage is implemented in [`2_Flexible_wall.ipynb`](2_Flexible_wall.ipynb).  

---

## Notes
**1. File paths**  
- Some paths inside the notebooks may need to be updated depending on your local directory structure.  

**2. Library compatibility**  
- The project relies on the [pythermalcomfort](https://pythermalcomfort.readthedocs.io/) library. Since APIs may change across versions, please refer to the official documentation if you encounter issues.  
