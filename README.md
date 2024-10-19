# Tabular and image data interpretability

## Task 1: Tabular Data Interpretability
### Dataset: 
You will use a dataset related to health data, specifically predicting diabetes.

### Model: 
Train a neural network model (MLP) to estimate the likelihood of diabetes.

### Steps:

**Exploratory Data Analysis (EDA)**: Analyze the dataset using correlation matrices and pair plots, investigate class imbalances, and detect outliers.

**Model Training**: Preprocess the data and train the MLP model on training, validation, and test splits.

**Model Evaluation**: Use metrics like accuracy, precision, recall, and F1 score to evaluate the model's performance.

**Interpretability Methods**: Apply LIME and SHAP methods to interpret the trained model. Analyze feature importance for different instances and compare the results of the two methods.

**Neural Additive Model (NAM)**: Implement the NAM model and compare it with other interpretability techniques, assessing its advantages in terms of performance and interpretability.
## Task 2: Image Data Interpretability
### Model: 
Use a pre-trained VGG16 model on the ImageNet dataset.

### Steps:

Apply Grad-CAM, Guided Backpropagation, and SmoothGrad methods to generate saliency maps for interpreting how the model makes decisions for specific image classifications.

Perform adversarial attacks on images and compare the saliency maps of the original and adversarial examples.


Feature Visualization: Use optimization techniques to generate visualizations that show what features the model focuses on when classifying images.
