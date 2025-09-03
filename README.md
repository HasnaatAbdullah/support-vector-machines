# support-vector-machines
This repository contains my implementation of Support Vector Machines (SVMs) for classification using Python. I used the Wine Quality Dataset to classify wines based on their chemical properties and color.
# Support Vector Machines (SVM) for Classification | Machine Learning Foundation

I completed this project as part of **Course 3, Part C** of the **Machine Learning Foundation** specialization.  
In this project, I implemented **Support Vector Machines (SVMs)** using **Python** and **Scikit-learn** to classify wine quality based on various chemical properties.  
I created this repository to share my code, learning process, and results.

---

## Project Overview
**Support Vector Machines (SVM)** are powerful supervised learning algorithms used for both classification and regression.  
In this project, I focused on **SVM for classification**, applying it to the **Wine Quality Dataset**.  
The dataset contains **chemical properties** of red and white wines along with **quality scores**.

Key goals of the project:
- Implement **SVM classification** using Scikit-learn.
- Experiment with **different kernels**: Linear, Polynomial, and RBF.
- Tune **hyperparameters** like `C` and `gamma`.
- Evaluate performance using accuracy and classification metrics.

---

## Dataset Information
For this project, I used the **Wine Quality Dataset** (`Wine_Quality_Data.csv`).  
The dataset includes chemical properties, wine color, and quality ratings.

### **Features (Inputs)**
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- Color *(Red/White)*

### **Target (Output)**
- **Wine Quality** — An integer score ranging from **3 to 9** (higher = better quality).

---

## Installation
Clone this repository and install the required dependencies:

```bash
git clone https://github.com/your-username/support-vector-machines-demo.git
cd support-vector-machines-demo
pip install -r requirements.txt
