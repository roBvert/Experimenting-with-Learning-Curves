<div align="center">

# 📈 Experimenting with Learning Curves

**Understanding Model Performance Through Visualization**

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

</div>

---

## 🎯 Overview

This repository explores the power of **learning curves** in machine learning to diagnose model performance and identify issues like overfitting and underfitting. Using real-world housing data, we demonstrate how to analyze and compare different models through comprehensive visualizations.

## 🌟 Key Features

- 📊 **Learning Curve Analysis**: Visualize training and validation scores across different dataset sizes
- 🏘️ **Housing Price Prediction**: Apply ML models to real-world housing data
- 🔍 **Model Comparison**: Compare multiple models (Model A & Model B) to identify the best performer
- 🎨 **Rich Visualizations**: Clear, interpretable plots to understand model behavior

## 📂 Repository Structure

```
Experimenting-with-Learning-Curves/
│
├── 📓 Main Jupyter notebook code/
│   └── housing.ipynb          # Main analysis notebook
│
├── 🖼️ Demonstation/
│   ├── LearningCurves.png     # Learning curve visualizations
│   ├── modelA.png             # Model A performance
│   └── ModelB.png             # Model B performance
│
└── 📄 README.md
```

## 🚀 Getting Started

### Prerequisites

```bash
python >= 3.11
jupyter notebook
scikit-learn
pandas
numpy
matplotlib
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/willow788/Experimenting-with-Learning-Curves.git
   cd Experimenting-with-Learning-Curves
   ```

2. **Install dependencies**
   ```bash
   pip install jupyter scikit-learn pandas numpy matplotlib
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook "Main Jupyter notebook code/housing.ipynb"
   ```

## 📊 Sample Results

Check out the `/Demonstation` folder for visualizations showing:
- Learning curves comparing training vs validation performance
- Model A and Model B performance comparisons
- Insights into overfitting/underfitting behavior

## 🧠 What Are Learning Curves?

Learning curves plot the model's performance on training and validation sets against the size of the training data. They help you:

- ✅ **Detect Overfitting**: When training score is high but validation score is low
- ✅ **Detect Underfitting**: When both scores are low
- ✅ **Determine Data Needs**: Whether more data would improve performance
- ✅ **Compare Models**:  Identify which model generalizes better

## 🛠️ Technologies Used

- **Python 3.11**: Core programming language
- **Jupyter Notebook**: Interactive development environment
- **Scikit-Learn**: Machine learning library
- **Matplotlib/Seaborn**: Data visualization
- **Pandas**: Data manipulation
- **NumPy**:  Numerical computing

## 📈 Workflow

1. Load and explore housing dataset
2. Preprocess and prepare data
3. Train multiple models
4. Generate learning curves
5. Analyze and compare results
6. Draw insights for model improvement

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page. 

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

**willow788**

- GitHub: [@willow788](https://github.com/willow788)

---

<div align="center">

**⭐ Star this repository if you found it helpful! **

Made with ❤️ and Python

</div>
