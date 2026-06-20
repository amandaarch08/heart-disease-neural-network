# Heart Disease Classification using Neural Network (MLPClassifier)

Mini project for Machine Learning course using Neural Network with **MLPClassifier** to classify heart disease based on patient medical attributes.

## Project Information

* **Name:** Amanda Damayanti
* **Student ID (NIM):** 202432027
* **Class:** Pembelajaran Mesin A

## Dataset

This project uses the **Heart Disease UCI Dataset**.

* **Source:** [Heart Disease UCI Dataset Repository](https://github.com/sharmaroshan/Heart-UCI-Dataset?utm_source=chatgpt.com)
* **Rows:** 303
* **Features:** 13 input features + 1 target
* **Task:** Binary Classification

  * `0` = No Heart Disease
  * `1` = Heart Disease

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

### 1. Import Libraries

Importing all required libraries for data analysis, visualization, preprocessing, and neural network modeling.

### 2. Data Loading

The dataset is loaded directly from GitHub using Pandas.

### 3. Exploratory Data Analysis (EDA)

* Display dataset shape and preview
* Statistical summary
* Missing value checking
* Target class distribution visualization
* Correlation heatmap visualization

### 4. Data Preprocessing

* Splitting features (`X`) and target (`y`)
* Train-test split (80:20)
* Feature scaling using StandardScaler

### 5. Building Neural Network Model

Using **MLPClassifier** with:

* Hidden Layers: `(100, 50)`
* Activation Function: `ReLU`
* Optimizer: `Adam`
* Maximum Iterations: `500`

### 6. Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Classification Report
* Confusion Matrix
* Loss Curve

### 7. Architecture Comparison

Comparing multiple configurations:

* `(100,50)` ReLU
* `(100,50)` Tanh
* `(200,100,50)` ReLU

## Results

Best model performance:

* **Accuracy:** 78.69%
* **Best Architecture:** `(100,50)`
* **Best Activation:** `Tanh`

## Key Findings

* Neural Network successfully performed binary classification on heart disease data.
* Feature scaling significantly improved model training performance.
* Tanh activation slightly outperformed ReLU on this dataset.
* Larger architectures did not necessarily improve performance due to the small dataset size.

## Conclusion

This project demonstrates that Neural Networks can effectively classify heart disease cases using the Heart Disease UCI dataset. Although the dataset is relatively small, the model achieved good performance and provided useful insights into the impact of architecture and activation functions.

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/yourusername/your-repository-name.git
```

2. Open the project in Jupyter Notebook.

3. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run all notebook cells sequentially.

## Author

Amanda Damayanti
