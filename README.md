# README

## Project Overview
This project builds a **personalized recommendation system** for Pratilipi stories using **Alternating Least Squares (ALS)** collaborative filtering. It processes user interactions, applies feature engineering, and trains an implicit feedback model to recommend relevant stories.

## Installation & Dependencies
To set up the environment, install the necessary dependencies:
```bash
pip install numpy pandas matplotlib seaborn scipy implicit tqdm pickle
```

## Running the Code
1. Ensure that dataset files (`user_interaction.csv`, `metadata.csv`) are placed in the correct directory.
2. Run the Python script (`pratilipiassignment.py`) step by step.
3. The script will:
   - Load and preprocess data.
   - Perform **exploratory data analysis (EDA)**, including outlier removal.
   - Train an **ALS-based recommendation model**.
   - Evaluate the model using **Precision@5**.
   - Generate and store **top 5 recommendations per user**.

## Project Structure
```
/ProjectFolder
│-- pratilipiassignment.py     # Main Python script
│-- data/
│   │-- user_interaction.csv   # User interaction dataset
│   │-- metadata.csv           # Metadata about stories
│-- README.md                  # This README file
│-- als_model.pkl              # Trained ALS model
│-- user_id_to_idx.pkl         # User ID mapping
│-- item_id_to_idx.pkl         # Item ID mapping
```

## Output
- **Visualizations**: Histogram and boxplot of read percentages, interaction trends over time.
- **Processed datasets**: Cleaned and transformed data for model training.
- **Trained Model**: ALS-based recommendation model.
- **Predictions**: Dictionary of top 5 recommended stories per user.
- **Saved Model & Mappings**: Serialized files for future use.

## Contact
For any questions, reach out to the project owner.
