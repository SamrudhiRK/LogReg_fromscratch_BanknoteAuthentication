# Logistic Regression from Scratch for Banknote Authentication   

## Project Overview  
This project implements **Logistic Regression from scratch** to classify banknotes as **authentic or counterfeit** based on extracted features. The model is trained using **Gradient Descent** and evaluated using accuracy metrics.  

## Dataset  
The data can be found at: https://archive.ics.uci.edu/dataset/267/banknote+authentication
The dataset contains numerical features extracted from banknotes :  
- **Variance**  
- **Skewness**  
- **Curtosis**  
- **Entropy**  
- **Target Variable:** `0` (Fake) or `1` (Authentic)  


## Implementation Steps  
1. **Data Preprocessing**  
   - Normalizing the features for better convergence  
   - Splitting data into **training and test sets**  

2. **Logistic Regression Model**  
   - Implementing **Sigmoid Function** for probability estimation  
   - **Binary Cross-Entropy Loss** as the cost function  
   - **Gradient Descent Optimization** for parameter updates  

## Requirements  
Install the required dependencies before running the notebook:  

```bash
pip install numpy pandas matplotlib
```

## How to Run the Project  
1. Clone this repository:  
   ```bash
   git clone https://github.com/SamrudhiRK/LogReg_fromscratch_BanknoteAuthentication.git
   ```
2. Navigate to the project folder:  
   ```bash
   cd logistic-regression-banknotes
   ```
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook logreg_banknotes.ipynb
   ```
## Results & Insights  
- **Logistic Regression successfully classifies banknotes** with high accuracy.  
- **Gradient Descent** optimizes the model for better predictions.  
- The model **performs well on unseen data**, demonstrating its effectiveness.  
