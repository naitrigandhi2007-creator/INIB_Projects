# 🌸 Iris Flower Classification using Machine Learning

A simple and interactive **Machine Learning web application** built with **Python** and **Streamlit** to classify Iris flowers into three species—**Setosa**, **Versicolor**, and **Virginica**—based on sepal and petal measurements.

## 🚀 Live Demo
🔗 **Project Link:** https://naitri-2007-inib-irisflowerclassificationproject.hf.space/#iris-flower-classification

---

## 📌 Project Overview

The Iris Flower Classification project uses the famous **Iris dataset** to train a machine learning model that predicts the species of an iris flower from four input features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The model is trained using the **k-Nearest Neighbors (k-NN)** classification algorithm and deployed as an interactive web application using **Streamlit**.

---

## ✨ Features

- 🌼 Predicts Iris flower species instantly.
- 🤖 Built using the k-Nearest Neighbors (k-NN) algorithm.
- 📊 Uses the classic Iris dataset from Scikit-learn/UCI Repository.
- 📈 Evaluates model performance using Accuracy, Precision, and Recall.
- 💻 Interactive Streamlit-based user interface.
- ☁️ Deployed on Hugging Face Spaces for public access.

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Machine Learning:** Scikit-learn
- **Data Handling:** Pandas, NumPy
- **Visualization:** Matplotlib
- **Web Framework:** Streamlit
- **Deployment:** Hugging Face Spaces

---

## 📂 Dataset

The project uses the **Iris Dataset**, one of the most popular datasets for introductory machine learning tasks.

- **Source:** UCI Machine Learning Repository
- **Instances:** 150
- **Features:** 4
- **Classes:** 3 (Setosa, Versicolor, Virginica)

---

## 🧠 Machine Learning Workflow

1. Load the Iris dataset.
2. Preprocess and prepare the data.
3. Split the dataset into training and testing sets.
4. Train the k-NN classification model.
5. Evaluate model performance using:
   - Accuracy
   - Precision
   - Recall
   - Confusion Matrix
6. Deploy the trained model using Streamlit.

---

## 📁 Project Structure

```text
Iris-Flower-Classification/
│── app.py
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Iris-Flower-Classification.git
cd Iris-Flower-Classification
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
streamlit run app.py
```

---

## 📊 Model Performance

| Metric | Score |
|----------|--------|
| Accuracy | ~96–100% |
| Precision | High |
| Recall | High |

*(Performance may vary slightly depending on the train-test split.)*

---

## 📸 Project Preview

After launching the app, users can input flower measurements and instantly receive the predicted Iris species.

---

## 📚 Future Improvements

- Add data visualization dashboard.
- Compare multiple ML algorithms.
- Save and load trained model using Joblib.
- Enhance UI with custom styling and animations.



---

⭐ If you found this project useful, feel free to **star the repository** and share your feedback!
