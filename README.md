# 🧠 Machine Learning Models in Python

This repository contains a collection of beginner-friendly machine learning models implemented using Python and `scikit-learn`. Each model uses real-world datasets and includes visualizations to demonstrate core machine learning algorithms.

## 🔍 Included Models

- **1_logistic_regression_sale_prediction.ipynb**  
  Predicts whether a customer will purchase a product using Logistic Regression.

- **2_knn_salary_classification.ipynb**  
  Classifies whether an employee’s salary is above or below 50K using K-Nearest Neighbors, based on features like age, education, capital gain, and working hours.

- **3_svm_digit_recognition.ipynb**  
  Recognizes handwritten digits using Support Vector Machine (SVM) on the `scikit-learn` digits dataset.

- **4_naive_bayes_titanic_survival.ipynb**  
  Predicts survival on the Titanic using Naive Bayes, based on features like age, gender, fare, and class.

## 📁 Folder Structure

- `data/` – Contains input CSV files and images used in the notebooks.
- `*.ipynb` – Jupyter Notebooks for each machine learning model.
- `requirements.txt` – Lists all required Python packages.
- `.gitignore` – Ignores virtual environment and unnecessary files.

## ⚙️ Setup Instructions (VS Code)

> These notebooks are designed to be run in **Visual Studio Code** with the **Jupyter extension**.

### ✅ Requirements

- Python 3.8 or higher
- [Visual Studio Code](https://code.visualstudio.com/)
- [Jupyter Extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

### 🐍 Set Up a Virtual Environment

1. Clone the repository and navigate to the project folder:
   ```bash
   git clone https://github.com/Tuhin-SnapD/Machine-Learning-Models
   cd Machine-Learning-Models
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv myenv
   # Windows
   myenv\Scripts\activate
   # macOS/Linux
   source myenv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### 🚀 Running the Notebooks

1. Open Visual Studio Code.
2. Ensure the Python and Jupyter extensions are installed.
3. Open any `.ipynb` file in the project.
4. Select the Python interpreter from your virtual environment (`myenv`) using the command palette (`Ctrl+Shift+P` > `Python: Select Interpreter`).
5. Run the notebook cells interactively by clicking the "Run Cell" buttons or using the keyboard shortcuts (e.g., `Ctrl+Enter`).

## 📌 Notes

- Datasets are either sourced from `scikit-learn` (e.g., digits dataset) or included as CSV files in the `data/` folder.
- Each notebook includes inline explanations, code, and visualizations for educational purposes.
- To run these notebooks in Google Colab, upload the `.ipynb` files directly to Colab.

## 📬 Contact

For questions, suggestions, or contributions, please open an issue or submit a pull request.