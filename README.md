#  Classification of Rock and Mine using Logistic Regression

This project applies **Logistic Regression** to classify sonar signals as either **rock** or **mine** using the **Sonar dataset** from the UCI Machine Learning Repository. This is part of a final project for the **Artificial Intelligence (SP25)** course at **COMSATS University Islamabad, Abbottabad Campus**.

##  Project Overview

Sonar signals are used to identify objects under the surface of water. This project uses **supervised learning** to train a binary classifier that distinguishes between sonar signals reflected by **metal cylinders (mines)** and **rock surfaces**.

The logistic regression model is chosen for its simplicity and effectiveness in binary classification tasks.

---

##  Authors

- **Ahsan Faraz** - *FA22-BSE-073*
- **Abban Khan** - *FA22-BCS-004*
- **Muhammad Hamza Hussain** - *FA22-BSE-160*

Supervisor: **Sir Muhammad Rafay Hannan**

---

##  Dataset

- **Source**: UCI Machine Learning Repository  
- **Link**: [Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))  
- **Attributes**: 60 features representing sonar signal energy in various frequency bands.  
- **Target**:  
  - **M** = Mine  
  - **R** = Rock

---

##  Requirements

Make sure you have the following Python packages installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
