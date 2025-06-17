# 📄 Resume Generation using Machine Learning

This project is designed to **predict candidate suitability** for resumes using a dataset of features and labels, helping automate early-stage recruitment decision-making. It uses supervised machine learning techniques to predict the likelihood of a candidate being shortlisted for a role.

## 🚀 Features
- Resume data preprocessing and visualization
- Training and evaluation of ML models (e.g., Logistic Regression, Random Forest)
- Prediction on new data (test set)
- Easy-to-use Jupyter Notebook workflow
- CSV file input/output for training and testing

## 📁 Project Structure
```
Resume-Generation/
├── Resume_Generator.ipynb     # Main Jupyter notebook for model training & prediction
├── train.csv                  # Training data containing resume features
├── test.csv                   # Test data for model prediction
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation
```

## 📊 Dataset Description
- **train.csv**: Contains labeled data with features like skill scores, education level, experience, etc.
- **test.csv**: Contains similar features, but without labels; used for generating predictions.

## ⚙️ How It Works
1. Load and preprocess the training and testing datasets.
2. Visualize important features to understand the data distribution.
3. Train various classification models.
4. Evaluate model accuracy, precision, recall, etc.
5. Predict outcomes on the test dataset.
6. Export the predictions if needed.

## 🧠 Technologies Used
- Python 3.8+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualizations)

## 💻 Setup Instructions

### Step 1: Clone the repository
```bash
git clone https://github.com/manasdarak10/Resume-Generation.git
cd Resume-Generation
```

### Step 2: Install dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Run the notebook
Open the Jupyter notebook:
```bash
jupyter notebook Resume_Generator.ipynb
```
