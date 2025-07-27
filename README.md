
---

## 📊 Dataset

The [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) is a classic classification dataset with 150 samples of 3 different flower species:

- Iris Setosa
- Iris Versicolour
- Iris Virginica

Each sample includes **4 features**:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 🧠 Neural Network Architecture

- **Input layer:** 4 neurons (features)
- **Hidden layers:** 3 layers with 8 neurons each
- **Activation Function:** ReLU
- **Output layer:** 3 neurons (one for each class)
- **Loss Function:** CrossEntropyLoss
- **Optimizer:** Adam

---

## 🛠️ Dependencies

Install all required Python libraries using:

```bash
pip install torch scikit-learn matplotlib
