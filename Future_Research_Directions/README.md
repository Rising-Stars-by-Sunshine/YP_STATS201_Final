# Future Research Directions



# Leveraging Causal Inference to Predict and Mitigate Student Dropout Rates: A Machine Learning Approach

## Background/Motivation:
Student dropout is a pervasive problem across educational institutions, leading to individual economic disadvantages and wider societal inequities (Rumberger, 2011). Understanding and predicting which students are at risk of dropping out can enable timely interventions, but traditional predictive models often fail to capture the causal relationships and may be biased by confounding variables. Furthermore, research in this realm has often focused on correlation rather than causation, which does not effectively inform interventions (Bowers, 2010). Addressing this gap, our research is motivated by the need to delineate the causal pathways that lead to student dropout and academic success.

## Research Questions:

- What are the causal relationships between student demographics, academic behaviors, institutional factors, and dropout risk?
- Can a machine learning model that accounts for causal inference improve the accuracy and efficacy of predictions about student dropout and academic success?
- How can the inclusion of causal inference in modeling inform effective and targeted interventions for at-risk students?

## Methods:
To address the complex interdependencies and causal relationships between observed variables, our research will employ a structured causal model (SCM) approach, using Directed Acyclic Graphs (DAGs) to identify and visually represent the treatment, target, and confounding variables (Pearl, 2009). The treatment variable (T) in this study will be specific academic interventions (e.g., tutoring services, financial aid), the target variable (Y) is student dropout/success, and the confounding variables (C) include student demographics, prior academic performance, and psychosocial factors.

Our machine learning model of choice is Counterfactual Regression, specifically the Causal Forest algorithm (Wager & Athey, 2018), which is adept at handling large datasets with many covariates, allows for the estimation of heterogeneous treatment effects, and is robust in the presence of complex confounder-treatment interactions. We will employ the grf package in R for its implementation (Tibshirani et al., 2019).

To estimate the causal effects, we will firstly utilize propensity score matching to balance the treatment and control groups regarding the confounding variables, then apply Causal Forest to estimate the potential outcome mean for each individual subject to treatment (Imbens & Rubin, 2015).

## Potential Results:
We anticipate that the Causal Forest model will identify non-linear relationships and complex interactions, resulting in accurate estimates of individualized treatment effects. By understanding these causal pathways, we expect to uncover which interventions are most beneficial for which students, facilitating more personalized and effective dropout prevention strategies.

## Contributions:
This research is poised to make significant contributions to educational scholarship and practice in several ways. Firstly, it advances the methodological frontier by applying causal inference within the context of machine learning to the pressing issue of student dropout. Secondly, it provides empirical evidence supporting the utility of SCM and Causal Forest in understanding and addressing complex educational phenomena. Finally, this approach can offer actionable insights for educators and policymakers by specifying which interventions are most likely to be effective for particular student subgroups.
