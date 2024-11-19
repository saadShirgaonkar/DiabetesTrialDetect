## README  

### Aim  
This project develops a **PyTorch model** to predict the **failure score** of Type 2 diabetes trials. The focus is on **interventional trials** since the dataset for **experimental trials** was insufficient (less than 200 samples). The workflow includes dataset preparation, cleaning, analysis, and model training.  

---

### File Structure  

#### **Folders**  
- **`Dataset/`**: Contains raw JSON files and processed CSV files.  
- **`models/`**: Stores trained PyTorch models.  

#### **Notebooks**  
1. **`DatasetCreation_1.ipynb`**  
   - Converts raw JSON files into CSV format.  
   - Selects relevant features for training the model.  
2. **`DataCleaningandAnalysis_2.ipynb`**  
   - Handles missing values and applies feature engineering.  
3. **`DataAnalysis_3.ipynb`**  
   - Conducts exploratory data analysis (EDA).  
   - Includes plotting graphs to derive insights.  
4. **`ModelTraining.ipynb`**  
   - Trains and validates the PyTorch model.  
   - Includes feature importance analysis and visualization.  

---

### How to Use  
1. **Dataset Preparation**:  
   - Run `DatasetCreation_1.ipynb` to create the processed CSV file from raw data.  
2. **Data Cleaning**:  
   - Use `DataCleaningandAnalysis_2.ipynb` to clean and preprocess the dataset.  
3. **Analysis**:  
   - Explore data insights using `DataAnalysis_3.ipynb`.  
4. **Model Training**:  
   - Train the failure prediction model using `ModelTraining.ipynb`.  

---

### Requirements  
- Python 3.8+  
- Jupyter Notebook  
- PyTorch  
- Pandas, NumPy, Matplotlib, Seaborn  

---

### Note  
The large JSON files used to create the dataset are **not included** in the `Dataset/` folder because they exceeded GitHub's 100 MB file size limit. You can get these files from [ClinicalTrials.gov](https://clinicaltrials.gov/search?cond=Type%202%20Diabetes&aggFilters=results:with%20without,status:com) if needed for reproducibility.
