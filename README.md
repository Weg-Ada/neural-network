# Neural Network

Comparative analysis of the quality of supervised and unsupervised learning for a selected medical diagnostics task.
Code created in the Google Colab repository.

* Supervised learning ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) https://colab.research.google.com/drive/1VaLoz3Wcsapqv8yg8HkiQtnlCrjh92bD

* Unsupervised learning ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) https://colab.research.google.com/drive/1A4wfASBTHelnRmKpIVKkopbwgCQN5Ilv

## Description of the research problem 

The aim of the study was to compare the quality of supervised and unsupervised learning methods in medical diagnostics. The accuracy of the classification was the main measure of comparing the two learning methods. Accuracy is the ratio of the number of correctly classified samples to the total number of samples available in the database. The analysis of the research results for the supervised and unsupervised learning methods was aimed at selecting the best method of the classification task for the selected data set.

* Supervised learning - learning by example, the system receives inputs and answers, and then performs the task of searching for rules.
* Unsupervised learning - the system's task is to analyze data and search for patterns, at the beginning of its operation, the system only has input data.

Technologies used:

* Python
* Keras
* Scikit-learn
* Google Colab

In the scientific community, the supervised method is mainly used for classification tasks. The research carried out in the work confirms the effectiveness of the above method, the results are clearly better. Despite the fact that the unsupervised method is not a commonly used classification system, in the conducted research it shows a very good result threshold and high stability depending on the individual operations on the algorithm parameters.

## Description of the dataset

Source of [Kaggle.com](https://www.kaggle.com/ronitf/heart-disease-uci)

### Context

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4.

### Content

Attribute Information:
* age
* sex
* chest pain type (4 values)
* resting blood pressure
* serum cholestoral in mg/dl
* fasting blood sugar > 120 mg/dl
* resting electrocardiographic results (values 0,1,2)
* maximum heart rate achieved
* exercise induced angina
* oldpeak = ST depression induced by exercise relative to rest
* the slope of the peak exercise ST segment
* number of major vessels (0-3) colored by flourosopy
* thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

The names and social security numbers of the patients were recently removed from the database, replaced with dummy values. One file has been "processed", that one containing the Cleveland database. All four unprocessed files also exist in this directory.

To see Test Costs (donated by Peter Turney), please see the folder "Costs"

### Acknowledgements

Creators:

    Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
    University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
    University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
    V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

Donor:
David W. Aha (aha '@' ics.uci.edu) (714) 856-8779

### Inspiration

Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0).

See if you can find any other trends in heart data to predict certain cardiovascular events or find any clear indications of heart health.
