# Literature

## Description:

The following content is the **LITERATURE** part of the project. This repository presents a paper representing machine learning methodologies, and a drafted research idea.

## 1.1 Paper Review

### What the DAAM: Interpreting Stable Diffusion Using Cross Attention
### Background and Motivation

- Application Scenarios/Broader Views: The research is crucial for understanding text-to-image generation models, like Stable Diffusion (Rombach et al., 2022), particularly how input words influence generated images, addressing ethical concerns and model transparency.

- Unsolved Issues/Problems Inspiring Research: The restricted access to major diffusion model weights by organizations has limited in-depth analysis (Tang et al., 2022). This research addresses the gap in understanding the dynamics of image synthesis in these models.

### Research Questions

- Intended Questions: The primary question is, "How does an input word influence parts of a generated image?" This includes understanding the syntactic and semantic relationships in image generation.

- Technical Difficulties in Existing Literature: Existing literature lacks a comprehensive analysis of how diffusion models interpret and process text inputs to generate images, especially at a fine-grained, pixel-level understanding.

### Methodology

- Data Source and Datasets: The study uses the Stable Diffusion model, pretrained on the LAION 5-billion image dataset.

- Machine Learning Algorithms: The research introduces diffusion attentive attribution maps (DAAM) for analyzing cross-attention in diffusion models.

- Software and Computing Platforms: Utilizes existing frameworks like the HuggingFace’s Diffusers library for model implementation and analysis.

### Potential Results

- Findings: DAAM provides insights into how specific words influence image generation, revealing syntactic and semantic relationships in generated images and highlighting issues like feature entanglement.

- Implications and Limitations: This method offers a novel way to interpret text-to-image models, aiding in ethical considerations and model improvements. However, it may have limitations in its applicability to different model architectures or datasets.

### Intellectual Merits and Impacts

- Advancement of Existing Research: Provides a new methodology for analyzing and understanding diffusion models, advancing the field of AI ethics and interpretability.

- Limitations and Further Extensions: Future research could extend this methodology to other models or use these findings to improve model robustness and ethical alignment. The study's limitations include potential model-specific biases.

- Real-world Applications: Insights from this research can guide the ethical development and deployment of AI models in creative industries.

- Potential Applications in Decision Making: The understanding gained from this research could inform policymakers and technologists in developing more responsible AI creative tools.

### Flowchart
<img src="Flowchart 1.png" alt="Flowchart">
Figure 1: Flowchart for section 1.1

## 1.2 Research Idea

### Background/Motivation:

Student dropout and degree completion are critical concerns in higher education, as they significantly impact both individual success and the broader socioeconomic landscape (Tinto, 1975; Pascarella & Terenzini, 2005). Despite the extensive research on student retention, a comprehensive understanding of the complex interplay between various predictive factors is yet to be fully realized. The ability to accurately predict dropout risk and identify elements that contribute to successful degree completion can empower educational institutions to implement timely interventions and improve academic support services (Bean & Metzner, 1985).

### Research Question:

The study aims to delve into the intricate web of variables affecting student outcomes by addressing two primary research questions:

- What specific predictive factors are associated with student dropout or successful degree completion?

- How do different features interact with each other to influence student outcomes?

### Application Scenarios:

The dataset for this investigation holds potential for several practical applications. It can facilitate the creation of predictive models that help identify at-risk students early, thereby enabling timely and effective intervention strategies to enhance student retention (Aguinis et al., 2013). Furthermore, the data can illuminate areas for institutional improvement to boost academic performance through targeted initiatives. Lastly, it supports equitable access to education by leveraging demographic information to design initiatives that address accessibility challenges faced by diverse student populations (Eagan et al., 2016).

### Methodology:

A multifaceted approach involving statistical analyses and machine learning techniques to decipher patterns and relationships within the dataset will be applied. This process begins with exploratory data analysis, followed by the development of predictive models to pinpoint the key determinants influencing student outcomes. Special attention will be given to understanding the interaction effects between different variables, which may provide additional insights into the mechanisms driving student success or failure.

### Results:

The anticipated results from this study include the identification of specific predictors linked to dropout or completion, along with an understanding of how these factors intertwine. Additionally, the study hopes to reveal the economic factors such as unemployment rate, inflation, and GDP's nuanced impacts on student success, thus providing a holistic perspective on the issue.

### Intellectual Merits/Practical Impacts:

This research holds dual significance. Intellectually, it contributes to the scholarly discourse on student success dynamics by unraveling the intricate interactions among diverse factors. Practically, its findings can directly inform and guide higher education administrators and policymakers in designing evidence-based strategies to enhance student retention and academic performance. Moreover, the insights gained from studying accessibility barriers will aid in closing equity gaps across different student populations, ultimately fostering a more inclusive and supportive learning environment (Redden, 2018).

### Flowchart
<img src="Flowchart 2.png" alt="Flowchart">
Figure 2: Flowchart for section 1.2

## Reference
```
@inproceedings{rombach2022highresolution,
  title={High-resolution image synthesis with latent diffusion models},
  author={Rombach, Robin and Blattmann, Andreas and Lorenz, David and Esser, Philipp and Ommer, Bj{\"o}rn},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={10684--10695},
  year={2022}
}

@article{tang2022what,
  title={What the daam: Interpreting stable diffusion using cross attention},
  author={Tang, Ruiqi and Liu, Lianmin and Pandey, Ankush and Jiang, Zhe and Yang, Guangyao and Kumar, Kartik and others},
  journal={arXiv preprint arXiv:2210.04885},
  year={2022}
}

@article{aguinis2013making,
  title={Making business school research more relevant for practice},
  author={Aguinis, Herman and Culpepper, Sheri A and Pierce, Charles A},
  journal={Journal of Management},
  volume={39},
  number={6},
  pages={1647--1668},
  year={2013},
  publisher={Wiley Online Library}
}

@article{bean1985conceptual,
  title={A conceptual model of nontraditional undergraduate student attrition},
  author={Bean, John P and Metzner, Barbara S},
  journal={Review of Educational Research},
  volume={55},
  number={4},
  pages={485--540},
  year={1985},
  publisher={SAGE Publications Sage CA: Los Angeles, CA}
}

@book{eagan2016american,
  title={The American freshman: National norms fall 2015},
  author={Eagan, Kevin and Stolzenberg, Ebony B and Ramirez, Joseph J and Aragon, Marisa C and Suchard, Marc R and Hurtado, Sylvia},
  year={2016},
  publisher={Higher Education Research Institute, UCLA}
}

@book{pascarella2005how,
  title={How college affects students: A third decade of research},
  author={Pascarella, Ernest T and Terenzini, Patrick T},
  year={2005},
  publisher={Jossey-Bass}
}

@article{redden2018closing,
  title={Closing the Gap},
  author={Redden, Elizabeth},
  journal={Inside Higher Ed},
  year={2018},
  note={Article}
}

@article{tinto1975dropout,
  title={Dropout from higher education: A theoretical synthesis of recent research},
  author={Tinto, Vincent},
  journal={Review of Educational Research},
  volume={45},
  number={1},
  pages={89--125},
  year={1975},
  publisher={SAGE Publications Sage CA: Los Angeles, CA}
}
```
