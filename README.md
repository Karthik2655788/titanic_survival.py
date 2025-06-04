# titanic_survival.py
# 🚢 Titanic Survival Prediction with Logistic Regression

This project is a simple implementation of a logistic regression model to predict passenger survival on the Titanic using a toy dataset. The model is trained to classify whether a passenger survived (`1`) or not (`0`) based on their ID (for demonstration purposes only).

## 📁 Project Structure

```
├── titanic_survival_prediction.py  # Main Python script
├── README.md                       # Project description
```

## 🧪 Dependencies

Ensure the following Python libraries are installed:

* `scikit-learn`
* `numpy`
* `matplotlib`

Install them with:

```bash
pip install scikit-learn numpy matplotlib
```

## 📊 Dataset (Toy Example)

This example uses a manually defined dataset:

```python
x_survived_ID = [[101], [102], [103], [104], [105]]
y_survived_or_not = [1, 1, 1, 0, 0]
```

* `x_survived_ID`: Passenger IDs (used as a dummy feature)
* `y_survived_or_not`: Survival status (1 = survived, 0 = did not survive)

> ⚠️ Note: In real scenarios, survival prediction would involve multiple features like age, sex, class, etc. This example is for educational purposes.

## ⚙️ Workflow

1. **Data Preparation**: Feature and label arrays are created manually.
2. **Train-Test Split**: 80% training and 20% testing using `train_test_split`.
3. **Model Training**: Logistic Regression from `sklearn` is used.
4. **Prediction**: Model predicts survival on the test set.
5. **Evaluation**: Accuracy is printed.
6. **Visualization**: A bar chart comparing actual vs predicted survival is displayed.

## 📈 Output Example

```
Predictions: [1]
Accuracy: 1.0
```

### 📊 Visualization

A bar graph is generated comparing actual and predicted survival values for the passengers in the test set.

![Example Chart - Actual vs Predicted](#)

## 📌 Notes

* The feature (Passenger ID) is not meaningful for real predictions and is used here only for demonstrating logistic regression and visualization.
* For a full Titanic dataset example, use data from [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data) with multiple features like `Pclass`, `Sex`, `Age`, `Fare`, etc.
