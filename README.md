# Perceptron Neural Network – Binary Classification on Iris Dataset 🌸

<p align="center">
  <img src="Output_Images/Perceptron_Banner.png" alt="Perceptron Neural Network Banner" width="80%">
</p>

Binary classification of Iris flowers using a Perceptron model with clear decision boundary visualization and confusion matrix.  

This mini project is part of my continuous practice in Machine Learning and basic Deep Learning concepts, implemented and documented with a clean Jupyter Notebook and visual outputs.

---

## 🔍 Visual Story

A quick visual overview of what this project does.

<p align="center">
  <img src="Output_Images/Iris%20Dataset%20-%20Binary%20Classification.png" alt="Iris Dataset - Binary Classification" width="45%">
  <img src="Output_Images/Decision%20Boundary.png" alt="Decision Boundary" width="45%">
</p>

<p align="center">
  <img src="Output_Images/Confusion%20Matrix%20-%20Perceptron.png" alt="Confusion Matrix - Perceptron" width="45%">
</p>

These visuals show how the Perceptron separates two Iris classes in 2D feature space and how well it performs on the test data.

---

## 📘 What this project demonstrates

- Implementation of a **Perceptron** model for binary classification on the classic Iris dataset.  
- Understanding Perceptron as a **basic Artificial Neural Network (ANN)** concept inside the broader Deep Learning / Machine Learning field.  
- Visualizing the learned **decision boundary** in 2D feature space.  
- Evaluating performance using a **confusion matrix** and simple metrics like accuracy.

---

## 📂 Project Overview

- Problem type: **Binary classification** (two Iris species).  
- Algorithm: **Perceptron Neural Network** (single-layer, linear decision boundary).  
- Input features: Two numerical features selected from the Iris dataset to allow 2D visualization.  
- Outputs: trained Perceptron decision boundary plot, confusion matrix heatmap, and a clear step-by-step notebook explaining the workflow.

---

## 📊 Dataset

- Base dataset: **Iris dataset** (popular ML dataset).  
- Classes: Filtered to **two classes** to make it a binary classification task.  
- Features: Selected two features (for example, sepal/petal measurements) to visualize data and boundary in 2D.  
- Preprocessing: data loading and selection of required columns, class filtering to convert multi-class Iris into binary, and a train-test split for evaluation.

---

## 🧠 Notebook Workflow

The main notebook in this repository is:

- `Binary Classification of Iris Flowers Using Perceptron Algorithm.ipynb`

Inside the notebook, you will find:

1. **Introduction & Problem Setup**  
   - Overview of the Iris dataset and binary classification objective.  
   - Short explanation of the Perceptron model.

2. **Data Loading & Exploration**  
   - Load the Iris dataset.  
   - Filter for two target classes.  
   - Select two features for 2D visualization.  
   - Basic plots to understand class separation.

3. **Data Preparation**  
   - Train-test split.  
   - Basic scaling/normalization steps if required for Perceptron training.

4. **Perceptron Model Training**  
   - Initialize and train the Perceptron model.  
   - Observe convergence and decision boundary behavior.

5. **Visualization**  
   - Plot the **Iris data points** in the chosen 2D feature space.  
   - Plot the **decision boundary** learned by the Perceptron.  
   - Show the **confusion matrix** as a heatmap.

6. **Evaluation & Insights**  
   - Compute accuracy and other basic metrics.  
   - Analyze the confusion matrix.  
   - Briefly discuss where the model performs well and where it misclassifies.

---

## 📈 Model Performance

- Task: Binary classification on a subset of the Iris dataset.  
- Evaluation:  
  - **Confusion Matrix**: shown above in the Visual Story section as “Confusion Matrix - Perceptron”.  
  - **Accuracy**: the model achieved **100%** accuracy on the test data.  

Even though the task is simple, getting 100% accuracy shows that the Perceptron is able to perfectly separate these two classes in the chosen feature space.

---

## 🧩 What I practiced in this project

- Working with the **Iris dataset** for a binary classification task.  
- Implementing a **Perceptron Neural Network** for a simple real-world dataset.  
- Understanding how a **linear decision boundary** separates two classes in feature space.  
- Generating and interpreting a **confusion matrix**.  
- Creating clean, meaningful **visualizations** to explain a model’s behavior.  
- Organizing a mini ML/ANN project on GitHub with a clear notebook and image outputs.

---

## ⚙️ How to run this notebook

1. **Clone the repository**

```bash
git clone https://github.com/adiratna89/Perceptron-Neural-Network-Binary-Classification.git
cd Perceptron-Neural-Network-Binary-Classification
```

2. **Create/activate a Python environment** (optional but recommended).

3. **Install required libraries**

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

4. **Open the notebook**

```bash
jupyter notebook "Binary Classification of Iris Flowers Using Perceptron Algorithm.ipynb"
```

Run the cells step by step to reproduce the results and visualizations.

---

## 🧭 Future improvements

Some ideas to extend this mini project:

- Implement a **Multi-Layer Perceptron (MLP)** and compare it with the single-layer Perceptron.  
- Try different **feature combinations** from the Iris dataset and see how the decision boundary changes.  
- Add **cross-validation** and more detailed metrics (precision, recall, F1-score).  
- Compare the Perceptron with other classifiers like **Logistic Regression, SVM, or k-NN** on the same binary task.  
- Turn this into a small part of a larger **Deep Learning practice series**.

---

## 📁 Repository Structure

```text
Perceptron-Neural-Network-Binary-Classification/
│
├── Binary Classification of Iris Flowers Using Perceptron Algorithm.ipynb
├── README.md
├── LICENSE                 # project license (MIT)
└── Output_Images/
    ├── Iris Dataset - Binary Classification.png
    ├── Decision Boundary.png
    └── Confusion Matrix - Perceptron.png
```

This structure keeps the main notebook, license, and visual outputs organized and easy to explore.

---

## 👤 Author

**Adiratna Kamble**  

- GitHub: [adiratna89](https://github.com/adiratna89)  
- LinkedIn: [linkedin.com/in/adiratna-kamble](https://www.linkedin.com/in/adiratna-kamble)  
- Email: adi8976839010@gmail.com  

This mini project is part of my journey in Python, Machine Learning, and Deep Learning basics, and my effort to continuously improve how I design and document ML projects on GitHub.

---

## 📄 License

This project is licensed under the **MIT License**.  
You are welcome to use or refer to this repository for learning purposes.
