# Repeat Purchase Prediction

## Authors

- ***Uppalapati Suchith Chowdary***

## Project Overview

- This project aims to predict whether a customer will make a repeat purchase from a seller.
- It leverages machine learning techniques to analyze user behavior and predict future purchases.
- The project includes data processing, feature extraction, model training, and evaluation.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, LightGBM,XGBoost, TensorFlow
- **Tools:** Jupyter Notebook

## Datasets

- **User Data:**
  - `User Data/user_info.csv`: Contains information about users.
  - `User Data/user_log.md`: Contains the link to download `user_log.csv` file having transaction details of every user.
- **Extracted User Data:**
  - `User Extracted Info/user_action.csv`: Contains user actions.
  - `User Extracted Info/user_day.csv`: Contains user activity by day.
- **Extracted Seller Data:**
  - `Seller Extracted Info/seller_action.csv`: Contains seller actions.
  - `Seller Extracted Info/seller_day.csv`: Contains seller activity by day.
- **Training and Testing Data:**
  - `train_format1.csv`: Training data in the original format.
  - `test_format1.csv`: Testing data in the original format.
  - `Train and Test Data/train_data.csv`: Processed training data.
  - `Train and Test Data/test_data.csv`: Processed testing data.
- **Training and Testing Data Similarity:**
  - `Train and Test Data/train_data_similarity.csv`: Training data with similarity features.
  - `Train and Test Data/test_data_similarity.csv`: Testing data with similarity features.

## Notebooks and Code

- `Code File.ipynb`: Jupyter notebook containing the code for data processing, model training, and evaluation.

## Plots

- `Feature Importance Plots/feat_imp_plot_gain.png`: Feature importance plot based on gain.
- `Feature Importance Plots/feat_imp_plot_split.png`: Feature importance plot based on split.

## Quick Start 🚀

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Repeat-Purchase-Prediction.git
   ```
2. Navigate to the project directory:

   ```bash
   cd Repeat-Purchase-Prediction
   ```
3. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook:

   ```bash
   jupyter notebook Code\ File.ipynb
   ```
