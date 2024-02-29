## Description
This section describes how the research answers the research questions based on the specific methods.

## Results

### Predictive Factors

<img src="SHAP.png" alt="SHAP">

**Figure 1: SHAP Results**

This figure is a summary plot showing the most important features affecting the model's output. Each point on the summary plot represents the SHAP value (a measure of the importance of each feature in the prediction) of a feature for an instance. The features are sorted by the sum of SHAP value magnitudes over all samples, where the color represents the value of the feature (from low to high). This visualization provides insights into which features are most important and how they influence the predicted outcome.

We can conclude using row "Age at enrollment", "Application mode_12", and **figure 2** that for higher education, students enrolled at lower age, specifically from 17 - 23, are significantly more likely to succeed.

### XGBoost

<img src="XGBoost.png" alt="XGBoost">

**Figure 2: XGBoost**

XGBoost offers significant potential in identifying students at risk of dropping out by analyzing complex interactions among various predictors such as demographic characteristics, financial circumstances, and socio-economic backgrounds. The removal of academic performance significantly increased the difficulty of model training. Despite the moderate test accuracy illustrated in the presented model results, the performance is acceptable, considering the challenging nature of social behavior prediction. The ability of XGBoost to handle a variety of data types, its robustness to outliers, and its capacity to capture nonlinear relationships make it particularly apt for educational data, which often involves heterogeneous features and imbalanced classes. Moreover, the model's test accuracy of approximately 78.79% is promising given the context and complexity of educational data, signaling that with further fine-tuning and by addressing issues like overfitting, the model could become an even more reliable tool. Leveraging the XGBoost algorithm can enable educational institutions to proactively deploy interventions and support mechanisms tailored to individual student profiles, thereby mitigating dropout rates and fostering an inclusive and supportive learning environment.

