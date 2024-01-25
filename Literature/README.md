# Literature

## Description:

The following content is the **LITERATURE** part of the project. This repository presents a paper representing machine learning methodologies, and a drafted research idea.

## 1.1 Paper review

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

### Reference

Rombach, R., Blattmann, A., Lorenz, D., Esser, P., & Ommer, B. (2022). High-resolution image synthesis with latent diffusion models. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 10684-10695).

Tang, R., Liu, L., Pandey, A., Jiang, Z., Yang, G., Kumar, K., ... & Ture, F. (2022). What the daam: Interpreting stable diffusion using cross attention. arXiv preprint arXiv:2210.04885.
