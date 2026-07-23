# Data Folder

This folder contains the dataset used in this project.

### ⚠️ Dataset Download
The dataset file `creditcard.csv` is 140MB+. Due to GitHub's 100MB file limit, it is hosted on Kaggle instead.

**Kaggle Dataset Link:**
[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### How to Download the Dataset

#### Option 1: Using Kaggle CLI
1. Install Kaggle CLI and set up your API token
```bash
pip install kaggle
kaggle datasets download -d mlg-ulb/creditcardfraud
unzip creditcardfraud.zip -d ./
```

#### Option 2: Using Python with kagglehub - No login required
```python
import kagglehub
import pandas as pd

# Download dataset and get the path
path = kagglehub.dataset_download("mlg-ulb/creditcardfraud")

# Load the CSV
df = pd.read_csv(f"{path}/creditcard.csv")
print(df.head())
```
