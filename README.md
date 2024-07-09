**Diabetes Prediction Model**
=============================

**Overview**
-----------

This repository contains a machine learning model that predicts whether a person has diabetes based on their characteristics. The model is trained on a dataset of patient features and uses logistic regression to make predictions.

**Dataset**
---------

The dataset used to train the model is the Pima Indians Diabetes Database, which contains 768 patient records with 8 features:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age

The target variable is `Outcome`, which indicates whether the patient has diabetes (1) or not (0).

**Model**
------

The model is a logistic regression model implemented in Python using scikit-learn. The model is trained on the scaled features and uses the following hyperparameters:

* Penalty: L2
* C: 1.0
* Max iterations: 1000

**Performance**
------------

The model achieves an accuracy of 0.83 on the test set. The classification report and confusion matrix are as follows:

       0       0.85      0.83      0.84       153
       1       0.81      0.84      0.82       155

accuracy                           0.83       308


**Usage**
-----

To use the model, simply run the `predict.py` script and pass in the patient features as input. The script will output a prediction of 0 (no diabetes) or 1 (diabetes).

**Requirements**
------------

* Python 3.8+
* scikit-learn 0.24+
* pandas 1.3+
* numpy 1.20+

**Contributions**
--------------
Contributions are welcome! We value your input and encourage you to actively participate in the project. If you have any ideas, suggestions, bug reports, or feature requests, please don't hesitate to open an issue on GitHub. Additionally, we appreciate any code contributions you may have. If you'd like to contribute code, please submit a pull request, and we will review it as soon as possible. Thank you for your support!

**License**
-------

This repository is licensed under the MIT License. See `LICENSE` for details.

**Author**
------
<p>SABYASACHI GHOSH</p>

**Contact**
-------
<p>sabyasachighosh008@gmail.com</p>

