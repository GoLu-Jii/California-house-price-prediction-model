# California-house-price-prediction-model

# California House Price Prediction 📈🏠

This project demonstrates how to predict California housing prices using linear regression (both from scratch and with scikit-learn) in Python. The workflow covers data preprocessing, model training, evaluation, and making predictions on new data—all illustrated in a Jupyter Notebook.

---

## 🚀 Features

- **California Housing Dataset**: Uses the real-world dataset from `sklearn.datasets`.
- **Custom Linear Regression**: Implements linear regression from scratch with gradient descent.
- **scikit-learn Comparison**: Benchmarks the custom model against `sklearn`'s `LinearRegression`.
- **Data Normalization**: Standardizes features for improved convergence and prediction accuracy.
- **Training Visualization**: Plots cost function reduction over iterations.
- **Performance Metrics**: Compares models using Mean Absolute Error (MAE) and Mean Squared Error (MSE).
- **Interactive Prediction**: Allows users to input new house features and predicts the median value.
- **Well-Commented**: Each code block is clearly explained for educational purposes.

---

## 📁 File Structure

```
.
├── 03_linear-regression_practice.ipynb   # Main Jupyter Notebook
├── README.md                             # Project documentation
```

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Install Requirements

This project mainly uses:
- numpy
- pandas
- matplotlib
- scikit-learn

Install them with:

```bash
pip install numpy pandas matplotlib scikit-learn
```

### 3. Open the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook 03_linear-regression_practice.ipynb
```

---

## 📊 Usage

1. **Load and Explore Data**: The notebook begins by loading the California housing dataset and displaying its features.
2. **Normalize Data**: Standardizes input features for optimal model performance.
3. **Train Custom Model**: Uses gradient descent to fit a linear regression model.
4. **Visualize Training**: Plots training cost over iterations.
5. **Compare with scikit-learn**: Trains a model using scikit-learn for benchmarking.
6. **Evaluate Performance**: Compares both models using MAE and MSE.
7. **Predict New House Price**: Enter new house features when prompted and get the predicted median price.

---

## ✨ Example Prediction

```
Enter the features of the new house.
Example:
4.0     # Median income
20.0    # House age
5.0     # Average rooms
1.0     # Average bedrooms
500.0   # Population
2.0     # Average occupancy
34.2    # Latitude(~32 to ~42)
118.4   # Longitude(~-124 to ~-114)

📊 Predicted Median House Price: $809,166.09
```

---

## 🤝 Contributions

Contributions, issues, and improvements are welcome! Please open a pull request or an issue for suggestions or bug reports.

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 📬 Contact

For questions or collaborations, reach out via [GitHub Issues](https://github.com/GoLu-Jii/California-house-price-prediction-model/issues).

---
