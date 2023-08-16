# Resume-Classification
This project involves classifying resumes into 25 categories using text preprocessing, TF-IDF feature encoding, and multiple classification models, ultimately selecting a Logistic Regression model for its consistent high accuracy and effective content categorization.

# Resume Classification Project Report
## Project Overview
In this project, we aimed to classify resumes into 25 different categories based on their content. The project involved various stages, including data preprocessing, feature engineering, and model building. The goal was to develop a model that accurately classifies resumes, facilitating efficient categorization for recruitment and analysis purposes.

### Project Steps
**Step I: Importing Libraries**

Imported essential libraries such as pandas, scikit-learn modules, and others to facilitate data manipulation, preprocessing, modeling, and evaluation.

**Step II: Importing Dataset**

The dataset containing resumes and their corresponding labels was imported for analysis and modeling.

**Step III: Data Cleaning and Preprocessing**

Noticed that certain documents contained irrelevant special characters, potentially introduced during database storage and retrieval. To address this, we performed text preprocessing steps including converting text to lowercase, removing URLs, hashtags, special characters, punctuation marks, newlines, non-ASCII characters, and leading/trailing spaces. Tokenization and stop word removal were applied to facilitate model understanding.

**Step IV: Dataset Overview**

The dataset consisted of 962 records and 25 different categories, each representing a type of resume.

**Step V: Data Cleaning Observations**

During data inspection, we observed the presence of special characters that could invalidate the resume content. This led us to implement rigorous preprocessing techniques.

**Step VI: Adding Labels to Target Variables**

Added labels to the target variables to represent the different categories of resumes.

**Step VII: Defining Independent and Dependent Variables**

Defined the independent variable (features) as the preprocessed resume text and the dependent variable as the resume categories.

**Step VIII: Feature Encoding Using TF-IDF**

Used the Term Frequency-Inverse Document Frequency (TF-IDF) technique to encode the textual data into a numeric format suitable for model training.

**Step IX: Data Splitting**

The dataset was split into training and test sets to assess model performance.

**Step X: Model Building**

Employed various classification algorithms, including Logistic Regression, Decision Tree Classifier, K-Neighbors Classifier, Multinomial Naive Bayes, AdaBoost Classifier, Gradient Boosting Classifier, Random Forest Classifier, XGBoost Classifier, and Support Vector Classifier.

**Step XI: Model Performance Evaluation**

Evaluated model performance using accuracy, precision, recall, F1-score, and balanced accuracy metrics on both the training and test sets.

**Step XII: Model Selection**

After comparing model performance, we selected the Logistic Regression model due to its consistent accuracy, precision, recall, F1-score, and balanced accuracy on both training and test datasets.

**Step XIII: Model Evaluation**

Performed a detailed evaluation of the selected model using classification reports and confusion matrices for both the training and test datasets.

**Step XIV: Cross-Validation**

Conducted cross-validation using accuracy as a metric, achieving a mean accuracy of approximately 99.44%.

**Conclusion**

Through meticulous data preprocessing, feature engineering, and comprehensive model evaluation, we successfully developed a resume classification model. The chosen Logistic Regression model demonstrated high accuracy and robust generalization, making it an optimal choice for automating the categorization of resumes for efficient recruitment processes.
