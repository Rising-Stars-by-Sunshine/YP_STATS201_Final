# Predicting Student Dropout and Academic Success Using Machine Learning

## Project information
- **Author**: Yian Pei, Applied Math - Computer science, Class of 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Final Project for [STATS 201 Introduction to Machine Learning for Social Science, 2024 Spring Term (Seven Week - First)] instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: I extend my deepest gratitude to Prof. Luyao Zhang, and all my classmates in STATS 201 for their unwavering guidance, expertise, and encouragement, which helped me finish this project.
- **Project Summary**: 
  - **Background/Motivation**

    Student dropout and degree completion are critical concerns in higher education, as they significantly impact both individual success and the broader socioeconomic landscape. Despite the extensive research on student retention, a comprehensive understanding of the complex interplay between various predictive factors is yet to be fully realized. The majority focus on student academic performance when predicting student academic success/failure. However, academic success is often influenced by a myriad of factors extending beyond traditional classroom performance. While academic aptitude undoubtedly plays a vital role, the interplay of socioeconomic background, demographic characteristics are also crucial factors.
    
  - **Research Questions**
    
    1. What predictive factors and how do they associate with student dropout or successful degree completion, particularly focusing on non-academic determinants such as socioeconomic background and student demographics?
    2. How can machine learning algorithms, particularly XGBoost, be leveraged to identify at-risk students for dropout based on their demographic profiles, financial circumstances, and social-economic backgrounds?
    - [ChatGPT's answers to the research questions](https://chat.openai.com/share/ab0e25b7-5643-45f1-8166-875faf88f075)

  - **Application Scenario (Data Source)**
    
    [Predict students' dropout and academic success](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention) on Kaggle. This dataset is supported by program "SATDAP - Capacitação da Administração Pública under grant POCI-05-5762-FSE-000191, Portugal".

  - **Methodology**

    Onehot Encoder and Label Encoder were used for data preprocessing. Then a model is trained using XGBoost. Finally, SHAP is introduced to provide visualization of the predictive factors.

  - **Results**
 
    In general, our findings suggest that students with a higher enrollment age, students facing financial challenges, and students with a lower socio-economic status of the parental background are more likely to dropout from higher education.

  - **Intellectual Merits and Practical impacts of your project**
    - Intellectual Merits: The project significantly advances the understanding of how machine learning algorithms, particularly XGBoost, can be applied to the robust analysis and prediction of student academic retention factors, contributing to the body of knowledge in educational data mining.
    - Practical Impacts: Implementing these research findings could lead to the development of targeted intervention programs in educational institutions, potentially decreasing dropout rates and fostering an enhanced, data-driven approach to student support and retention strategies.


## Table of Contents

1. [**Literature**](./Literature)
2. [**Method**](./Method)
3. [**Data**](./Data)
    - 3.1 [Queried-Data](./Data/Queried_Data)
    - 3.2 [Processed-Data](./Data/Processed_Data)
4. [**Code**](./Code)
    - 4.1 [Data-Analysis](./Code/Data_Analysis)
    - 4.2 [Data-Query](./Code/Data_Query)
5. [**Results**](./Results)
6. [**Spotlights**](./Spotlights)
7. **More about the Author**
8. **References**

## Literature

In the realm of higher education retention studies, Tinto's (1975) pioneering Model of Student Departure has been instrumental in shaping our understanding of academic predictors of student persistence. The expanding literature underscores the importance of non-academic factors in student retention, as delineated by Rumberger and Lim (2008), who highlight the influence of personal and external commitments on attrition rates. The adoption of advanced analytical approaches is exemplified by Baker and Inventado's (2014) exploration into the use of machine learning in educational contexts, setting the stage for proactive identification of at-risk students. Shahiri et al. (2015) further contribute to this domain, demonstrating the effectiveness of the XGBoost algorithm in predicting educational outcomes. Subsequent research builds upon these findings, incorporating a broader range of non-academic factors to refine the framework for student retention and leveraging the XGBoost algorithm for more precise educational forecasting. This enhanced analytical capability facilitates the creation of tailored intervention strategies, aligning with Baker and Inventado's (2014) emphasis on socio-demographic insights, thus providing a solid foundation for personalized educational support systems aimed at improving retention.

## Method

The methodology rests on the application of the XGBoost algorithm, chosen for its efficiency and capability in managing diverse data types, as described by Chen and Guestrin (2016). The machine learning workflow for the model includes data processing steps, such as the removal of certain variables to maintain focus on non-academic predictors and applying one-hot encoding to categorical data.
The presentation of the model’s results involves training and testing splits, along with data visualization techniques including confusion matrices and ROC curves, which provide insights into the model’s discriminative power. Evaluation criteria like accuracy, precision, recall, and F1-score offer a multifaceted assessment of model performance.

## Data

The dataset can be queried from [kaggle](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention).
This dataset presents a comprehensive overview of undergraduates across diverse programs at a higher education institution. It encompasses demographic details, socio-economic indicators, and academic performance data, facilitating an analysis of potential factors influencing student dropout and success. The dataset comprises disparate databases with pertinent information recorded at enrollment, covering application mode, marital status, chosen courses, and more. Moreover, it allows the estimation of overall student performance each semester, considering credited/enrolled/evaluated/approved curricular units and their corresponding grades. Additionally, regional unemployment rate, inflation rate, and GDP offer insights into how economic factors impact student outcomes. This robust analytical tool sheds light on motivations behind students' persistence or abandonment across disciplines like agronomy, design, education, nursing, journalism, management, social service, and technology.

## Code

The Code contains data preprocessing, model training, and applying SHAP to model.

## Spotlight
    
## More About the Author

<img src="photo1.jpg" alt="photo">

### **Self Introduction**
Hello, I am Yian Pei, a passionate and dedicated individual currently pursuing a dual degree program at Duke Kunshan University (DKU) and Duke University, set to graduate in July 2025. My academic journey has been complemented by valuable research experiences and a commitment to personal and professional growth.

### **Professional Growth**

Professionally, my journey has been enriched by valuable experiences, from a research stint at the Suzhou Institute of Nano-Tech and Nano-Bionics to an Algorithm Engineer Internship at Ainstec. These experiences, coupled with my role as a Student Research Intern in Bioinformatics, have equipped me with a versatile skill set crucial for navigating the complex intersection of healthcare and artificial intelligence. The course has been instrumental in shaping my ability to integrate skills effectively, creating a robust professional profile poised for meaningful contributions.

### **Intellectual Growth**

Throughout this course, I've experienced substantial intellectual growth, particularly in understanding the profound impact of applying machine learning to address social issues globally, such as academic issues.

### **Living a Purposeful Life**

Envisioning the future, I aspire to be a pioneer in the field, contributing to advancements recognized globally. Winning the Nobel Prize or Turing Award is not just a personal dream; it's a testament to the impact I hope to make.

My purpose is to be the founding figure of transformative advancements, leaving a legacy that positively influences the intersection of artificial intelligence and healthcare.
