
# Preprocessing-Home-Credit

### Project Description
This project focuses on preprocessing data for a classification model to predict customer default risk based on demographic and financial data from the Home Credit dataset. The preprocessing steps address data cleansing, feature engineering, class imbalance, and data scaling to prepare the dataset for modeling.

### Data Source
The dataset can be downloaded from [Kaggle: Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/data).

### Files in Repository
- **[Preprocessing - Byte Me.ipynb](https://github.com/hijirdella/Preprocessing-Home-Credit/blob/main/Preprocessing%20-%20Byte%20Me.ipynb)**: Jupyter Notebook detailing the data preprocessing process, including data cleaning, feature engineering, and handling class imbalance using Python.
- **[Preprocessing - Byte Me.pdf](https://github.com/hijirdella/Preprocessing-Home-Credit/blob/main/Preprocessing%20-%20Byte%20Me.pdf)**: PDF report summarizing the preprocessing process and methods used.
- **README.md**: This file, providing an overview of the project, dataset, and files.

### Preprocessing Steps

#### Data Cleansing
- **Handling Missing Values**: Missing values are filled using appropriate methods like mean or mode.
- **Removing Duplicates**: Duplicates are checked and removed to ensure data integrity.
- **Handling Outliers**: Outliers in certain columns are identified and treated to reduce skewness.
- **Feature Transformation**: Log transformation and scaling are applied to normalize feature distributions.
- **Feature Encoding**: Binary and one-hot encoding are applied to categorical variables.
- **Class Imbalance**: SMOTE is used for oversampling minority classes, and RandomUnderSampler for undersampling majority classes to balance the dataset.

#### Feature Engineering
- **Feature Selection**: Removal of irrelevant features that do not contribute to the model's predictive power.
- **Feature Extraction**: Creation of new features, such as income-to-credit ratio, to enhance model performance.

### Project Structure
```
├── Preprocessing - Byte Me.ipynb      # Preprocessing steps in Jupyter Notebook
├── Preprocessing - Byte Me.pdf        # Preprocessing process report
├── README.md                          # Project overview
```

### How to Run the Project

1. **Clone this repository**:
   ```bash
   git clone https://github.com/hijirdella/Preprocessing-Home-Credit.git
   cd Preprocessing-Home-Credit
   ```

2. **Download the dataset** from [Kaggle](https://www.kaggle.com/competitions/home-credit-default-risk/data) and place it in the appropriate directory.

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Notebook**:
   - Open `Preprocessing - Byte Me.ipynb` in Jupyter Notebook to view and run the preprocessing steps.
   - Alternatively, refer to `Preprocessing - Byte Me.pdf` for a summary report of the preprocessing process.

### Notes
Ensure that the dataset path is correctly set in the notebook. The dataset is not included in this repository for privacy and security reasons.
