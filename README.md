# Diabetes Dataset Feedforward Neural Network Project

This project involves training a feedforward neural network using the diabetes dataset. The neural network is designed to predict the presence or absence of diabetes based on various parameters related to health and pregnancies.

## Dataset

The dataset contains the following parameters:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function (a function that scores the likelihood of diabetes based on family history)
- **Age**: Age in years
- **Outcome**: Class variable (0 if non-diabetic, 1 if diabetic)

## Model Training

The model is trained using the following steps and libraries:

### Libraries Used

- *numpy* for numerical operations
- *pandas* for data manipulation
- *matplotlib* for plotting
- *scikit-learn* for data preprocessing (train-test split, standardization)
- *tensorflow* for building and training the neural network
- *imbalanced-learn* for handling class imbalance using Random Oversampling

### Data Preprocessing

- The dataset is split into features (X) and the target (y).
- Standardization is performed using *StandardScaler* from *scikit-learn*.
- Random Oversampling is applied to handle class imbalance using *RandomOverSampler* from *imbalanced-learn*.

### Model Architecture

- A feedforward neural network is built using *TensorFlow*.
- The architecture may vary based on experimentation and requirements.

### Model Training and Evaluation

- The model is trained using appropriate loss functions, optimizers, and evaluation metrics.
- Training performance and evaluation results are monitored and analyzed.
