# E-Commerce Data Preprocessing and Cleaning

The first part of the project is dedicated to the pre-processing, cleaning and basic analysis of three datasets related to e-commerce.

## data_preprocessing notebook structure

The project uses data from Kaggle:

1. **Superstore dataset** (from jacopoferretti)
2. **E-commerce product recommendations** (from kartikeybartwal)
3. **Customer behavior dataset** (from uom190346a)

### What the notebook does

- Downloads and unzips Kaggle archives
- Reads CSV files and outputs an initial overview
- Cleans the data:
  - Processes skips
  - Removing and replacing outliers
  - Type conversion and date parsing
  - Creates new features (feature engineering)
- Saves cleaned versions to `data/processed/`.

### Libraries

The project uses the following Python libraries:
- `pandas`, `numpy`.
- `seaborn`, `matplotlib`.
- `sklearn.preprocessing`
- `scipy.stats`
- `kaggle`.

### Project Status

Currently completed:
- Downloading and basic data processing
- Providing basic EDA
- Cleaning and visualization for each dataset

###  TO DO

- Select the most suitable of three available datasets
- Perform data scaling
- Identify and select relevant variables
- Process variables of object type
- Fully prepare dataset for clustering