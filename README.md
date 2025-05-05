
 # Heart Disease Prediction

This project aims to predict whether a person has heart disease based on various health features using a Random Forest classifier. The dataset used is the Heart Disease dataset, commonly available on Kaggle. The model is built using Python and the Scikit-learn library.


## Dataset

The dataset used in this project is a heart disease prediction dataset, containing the following features:

- `age`: Age of the person
- `sex`: Gender (1 = male, 0 = female)
- `cp`: Chest pain type (categorical)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol
- `fbs`: Fasting blood sugar (1 = true, 0 = false)
- `restecg`: Resting electrocardiographic results (categorical)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise induced angina (1 = yes, 0 = no)
- `oldpeak`: Depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia (categorical)
- `target`: 1 if the person has heart disease, 0 if not (target variable)

## Requirements

This project requires the following Python libraries:

- pandas
- scikit-learn
- numpy

You can install the required dependencies using:
pip install -r requirements.txt
 ###Evaluation metrics
 ```
* **Accuracy:** The model achieves 98.54% accuracy, indicating overall high performance.
* **Precision:** It has high precision, particularly for predicting heart disease (class 1) with 100% precision.
* **Recall:** The recall is excellent, correctly identifying 97% of heart disease cases.
* **F1-Score:** The F1-score of 0.99 for both classes shows a good balance between precision and recall.
* **Support:** The model was tested on 205 instances, with nearly equal distribution between the two classes.
```



