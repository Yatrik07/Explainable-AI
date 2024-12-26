# Explainable AI (XAI) - Notebook

## Overview
This repository contains a comprehensive Jupyter Notebook that explores the principles, techniques, and implementations of Explainable AI (XAI). The notebook aims to provide insights into how AI models make decisions, ensuring transparency and interpretability for users and stakeholders.

## Key Features
- **Introduction to Explainable AI**  
  Understand the importance of explainability in AI and why it matters in critical domains.
- **Permutation Importance**  
  Learn how permutation-based techniques measure the impact of each feature by randomly shuffling its values.
- **SHAP (SHapley Additive exPlanations)**  
  - **SHAP Kernel Explainers**  
    Kernel-based SHAP explainers provide model-agnostic insights into feature importance.
  - **Using SHAP Visualization**  
    Visualize feature contributions to individual predictions.  
    *Example: Dependent feature - chance of admission*
  - **Global Explainability**  
    Analyze the overall explainability of the entire model.  
    *Example: Waterfall plot on a feature*
- **LIME (Local Interpretable Model-Agnostic Explanations)**  
  - **LimeTabularExplainer**  
    LIME's local explanations highlight how specific features influence individual predictions, contrasting with SHAP’s global approach.
  - **LIME Text Explainer**  
    Explains text classification models by perturbing input data.
  - **LimeImageExplainer**  
    Apply LIME to explain image-based models by masking portions of the input.

## Practical Implementations
Code demonstrations using Python and popular libraries such as scikit-learn and TensorFlow.

## Dataset
The dataset used in this project can be found [here](https://www.kaggle.com/nitindatta/graduate-admission-chances/data?select=Admission_Predict_Ver1.1.csv).

## Case Studies
Real-world examples showcasing how explainable AI enhances trust and accountability.

## Requirements
Ensure the following dependencies are installed:
- Python 3.x
- Jupyter Notebook
- scikit-learn
- SHAP
- LIME
- TensorFlow
- Matplotlib
- Pandas
- Numpy

Install the required packages using:
```bash
pip install -r requirements.txt
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Yatrik07/Explainable-AI
   ```
2. Navigate to the directory:
   ```bash
   cd explainable-ai-notebook
   ```
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the notebook and follow the instructions step by step.

## Structure
```
/ExplainableAI
├── explainable_ai_notebook.ipynb
└── requirements.txt
```

## Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements.

## Contact
For questions or suggestions, reach out via [LinkedIn](https://www.linkedin.com/in/yatrik-shah-7490481b6/) or [email](mailto:yatriksshah@gmail.com).




