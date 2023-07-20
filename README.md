# Detection of Monkeypox Cases Based on Symptoms Using XGBoost and Shapley Additive Explanations Methods

This repository contains the code and dataset for the article "Detection of Monkeypox Cases Based on Symptoms Using XGBoost and Shapley Additive Explanations Methods" published in Diagnostics.

**Authors**
- Alireza Farzipour ([LinkedIn](https://www.linkedin.com/in/afrzp))
- Roya Elmi ([LinkedIn](https://www.linkedin.com/in/royaelmi))
- Hamid Nasiri ([LinkedIn](https://www.linkedin.com/in/hamid-nasiri-b5555487/))

**Abstract**:
The monkeypox virus poses a novel public health risk that might quickly escalate into a worldwide epidemic. In this study, we have created a dataset based on the data collected and published by Global Health and used by the World Health Organization (WHO). The dataset contains textual information about the symptoms and the monkeypox disease. We applied gradient boosting methods, such as Extreme Gradient Boosting (XGBoost), CatBoost, and LightGBM, along with other standard machine learning methods such as Support Vector Machine (SVM) and Random Forest, to analyze the data. The goal was to develop a machine learning model that can diagnose monkeypox based on symptoms. XGBoost showed the best performance with an accuracy of 1.0 in reviews. We also used Shapley Additive Explanations (SHAP) to examine and explain the output of the XGBoost model.

**Keywords**: monkeypox, XGBoost, SHAP, MPXV, machine learning

## Code Execution
The code is organized into the following files:

- `Main.ipynb`: This file contains the code for training the machine learning models, including XGBoost, CatBoost, LightGBM, SVM, and Random Forest, and all performance measures.
- `Data.csv`: This file contains the used data.

To run the code, follow these steps:
1. Clone this repository: `https://github.com/alirezafarzipour/MonkeyPoxDetection.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open `Main.ipynb` using Jupyter Notebooks, Google Colab, and more.

Just so you know, you may need to adjust the file paths and parameters in the code to fit your environment and dataset.

## Contact Me
For any questions or inquiries, please contact Alireza Farzipour at alirezafarzipor@gmail.com or via [LinkedIn](https://www.linkedin.com/in/afrzp).

## Citation
If you find this work useful, please consider citing:

Farzipour, A.; Elmi, R.; Nasiri, H. Detection of Monkeypox Cases Based on Symptoms Using XGBoost and Shapley Additive Explanations Methods. Diagnostics 2023, 13, 2391. [Link to the article](https://www.mdpi.com/2075-4418/13/14/2391)

