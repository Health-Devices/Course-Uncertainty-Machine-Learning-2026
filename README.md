# Uncertainty Evaluation in Engineering Measurements and Machine Learning

---

Instructor: Miodrag Bolic, University of Ottawa, Ottawa, Canada<br/> www.site.uottawa.ca/~mbolic <br/>
Time and place:  Winter 2026, Wednesday 2:30 - 5:30 <br/>
Course code: ELG 5218, CSI 5218, EACJ 5600 <br/>
Syllabus: [Syllabus 2026](/Syllabus2.pdf)
<br>
### Course information

### Topics

**Lecture**  
[Intro slides](/Lec1/Lec_intro.pdf)

---
### [Topic 1 Probabilistic reasoning](/Lec1)
**Lecture**  
[Lec1](/Lec1/Lec1.pdf) \
[Lec 1 Notebook](/Lec1/Lec1_Bayesian_Modeling.ipynb)

Reading: Chapters 1 and 2 from [Villani, Mattias, (2025), Bayesian Learning.](https://github.com/mattiasvillani/BayesianLearningBook/raw/main/pdf/BayesBook.pdf)\
Probability refresher material related to "Math for machine learning": [Prince, Simon J.D. (2025). Understanding Deep Learning](https://udlbook.github.io/udlbook/)


---
### [Topic 2 Bayesian Inference for Gaussians, Bayesian linear and logistic regression](/Lec2)
**Lecture**  
[Gaussian Formulas](/Lec2/GaussianFormulas.pdf) \
[Lec2 Gaussian Estimates](/Lec2/GaussianModels.pdf) \
[Lec2 Bayesian Linear regression - from slide 19 by prof. Rao](/Lec2/tpmi_w19_lec5_slides_print.pdf)


Reading: Chapters 2, 3.3, 5 from [Villani, Mattias, (2025), Bayesian Learning.](https://github.com/mattiasvillani/BayesianLearningBook/raw/main/pdf/BayesBook.pdf)\

Code: [Lec 2 Notebook1](/Lec2/Gaussian_Models_Final.ipynb) \
[Lec 2 Notebook2, Bayesian Regression Using NumPyro](https://num.pyro.ai/en/stable/tutorials/bayesian_regression.html)

---

### [Topic 3 Bayesian logistic regression, Monte Carlo Sampling](/Lec3)
**Lecture**  
[Lec3 Bayesian Logistic regression](/Lec3/LogisticRegression.pdf) \
[Lec3 MCMC](/Lec3/MCMC.pdf) \
[Lec3 Langevin Monte Carlo](/Lec3/LangevinMC.pdf)

Code: [Lec 3 Notebook1: Laplace Approximation + Logistic Regression](/Lec3/Laplace_Approximation_Logistic_Regression.ipynb) \
[Lec 3 Notebook2, Markov Chains and MCMC](/Lec3/Lec3a_python_numpyro.ipynb) \
[Lec 3 Notebook3, Drift–Diffusion Processes and Langevin Monte Carlo](/Lec3/langevin_MALA.ipynb)

Reading: Chapters 8.2 and 10 from [Villani, Mattias, (2025), Bayesian Learning.](https://github.com/mattiasvillani/BayesianLearningBook/raw/main/pdf/BayesBook.pdf)\
[Roy Friedman, A Simplified Overview of Langevin Dynamics, 2022.](https://friedmanroy.github.io/blog/2022/Langevin/)

---

## [Topic 4 Kalman and particle filters](/Lec4)
**Lecture**  
[Lec4 State space models](/Lec4/ssm_slides.pdf) \
[Lec4 Kalman filter](/Lec4/Kalman_filter_slides.pdf) \
[Lec4 Particle filters](/Lec4/Particle_filter_slides.pdf)

Code: [Lec 4 Notebook1: Kalman Filters](/Lec4/ssm_examples.ipynb) \
[Lec 4 Notebook2, Particle fitlers](/Lec4/bearings_only_particle_filter.ipynb) \
[Kalman and Bayesian Filters in Python by Roger Labbe](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python)

Reading:
Chapters 17 from [Villani, Mattias, (2025), Bayesian Learning.](https://github.com/mattiasvillani/BayesianLearningBook/raw/main/pdf/BayesBook.pdf)\
[Bayesian Filtering and Smoothing by Simo Sarkka, chapters 4 and 7](https://users.aalto.fi/~ssarkka/pub/cup_book_online_20131111.pdf)\
[Kalman and Bayesian Filters in Python by Roger Labbe](https://drive.google.com/file/d/0By_SW19c1BfhSVFzNHc0SjduNzg/view?resourcekey=0-41olC9ht9xE3wQe2zHZ45A)

---
## [Topic 5 Variational inference](/Lec5)
**Lecture**  
[Lec5 Variational inference](/Lec5/VariationalInference.pdf)

Code: [Lec 5 Notebook1: VI](/Lec5/From_entropy_to_SVI.ipynb) \
[Stochastic Variational Inference with NumPyro](https://phuijse.github.io/BLNNbook/chapters/variational/svi.html)

Reading:

---
## [Topic 6 Variational Autoencoders and Bayesian Neural Networks](/Lec6)
**Lecture**  
[Lec6 Neural Networks as Parameterizers of Probability Distributions](/Lec6/NN_Parameterization.pdf) \
[Lec6 Variational autoencoders](/Lec6/VAE.pdf) \
[Lec6 Bayesian neural networks](/Lec6/BNN.pdf)

Code: [Lec 6 Notebook1: NN Parameterization Notebook](/Lec6/NN_Parameterization_Notebook.ipynb) \
[Lec 6 Notebook2: VAE for Breathing Anomaly Detection](/Lec6/VAE_Breathing_Anomaly.ipynb) and [Slides](/Lec6/VAE_Breathing_Anomaly.pdf) \
[Lec 6 Notebook3: BNN Notebook](/Lec6/Bnn_notebook.ipynb)

Reading: An Introduction to Variational Autoencoder by D.P. Kingma and M. Welling.\
[Variational Autoencoder](https://phuijse.github.io/BLNNbook/chapters/neural_networks/vae.html), chapter from Bayesian Learning and Neural Networks by Pablo Huijse. \
[Bayesian Neural Networks with numpyro](https://phuijse.github.io/BLNNbook/chapters/neural_networks/bayesian.html), chapter from Bayesian Learning and Neural Networks by Pablo Huijse. \
[DPM 2 - Variational Inference for Deep Continuous LVMs](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/DL2/deep_probabilistic_models_II/tutorial_2b.html) by Wilker Aziz.

---
## [Topic 7 Calibration and Conformal Prediction](/Lec7)
**Lecture**  
[Lec7 Proper Scoring Rules and Calibration](/Lec7/Proper_Scoring_Rules_and_Calibration.pdf) \
[Lec7 Conformal Prediction](/Lec7/Conformal_Prediction.pdf)

Code: [Lec 7 Notebook: Calibration](/Lec7/calibration_lab_notebook.ipynb) \
[Lec 7 Notebook: Conformal Prediction](/Lec7/conformal_prediction_lab_notebook.ipynb)

Reading: Kevin P. Murphy. Probabilistic Machine Learning: Advanced Topics. (Calibration + proper scoring rules, Sec. 14.2 and 14.3) \
[Calibration Tutorial](https://github.com/luferrer/CalibrationTutorial)
[Conformal Prediction](https://github.com/aangelopoulos/conformal-prediction)


---
## [Topic 8 Sensor Fusion](/Lec8)
**Lecture**  
[Lec8 Sensor Fusion and Association](/Lec8/Sensor_Fusion.pdf)


Code: [Lec 8 Notebook: Sensor Fusion and Association](/Lec8/notebook_traditional_fusion.ipynb) \
[Lec 8 Notebook: Covariance intersection](/Lec8/ci_vs_kf.ipynb)

Reading:
Li, X. R., & Jilkov, V. P. (2001).  
**Survey of maneuvering target tracking: III. Measurement models.**  
*Signal and Data Processing of Small Targets*, SPIE.

---

## [Topic 9 Diffusion models](/Lec9)
**Lecture**  
[Lec9 Diffusion Models](/Lec9/Diffusion_Models_Uncertainty_in_ML_course_2026.pdf) \
[Lec9 Sample generated image by diffusion model
](/Lec9/GeneratedSample.pptx)


Code: [Lec 9 Notebook: Diffusion Models Nodebook](/Lec9/Diffusion_Session_Notebook_v2.ipynb) \
[Lec 9 Notebook: Real DiffusionDet inference demo](/Lec9/DiffusionDet_real_inference_demo.ipynb) \
[SANA diffusion trajectory notebook](/Lec9/SANA_diffusion_trajectory_notebook.ipynb) 

Reading:
Chen, Shoufa, et al. "Diffusiondet: Diffusion model for object detection." Proceedings of the IEEE/CVF international conference on computer vision. 2023.

---
## [Topic 10 Multimodal Learning and Attention](/Lec10)
**Lecture**  
[Lec10 Multimodal Learning](/Lec10/MultimodalLearning.pdf) \
[Lec10 Attention, Transformers, and Fusion](/Lec10/AttentionTransformerFusion.pdf)

Code: [Lec 10 Notebook: Attention and Fusion](/Lec10/AttentionFusion.ipynb)

Videos:\
[Attention and Transformers](https://www.youtube.com/watch?v=RQowiOF_FvQ), Lecture 8, Stanford CS231N, Spring 2025.

[Multimodal Transformers](https://www.youtube.com/watch?v=90AGqQYYZc0&list=PL-Fhd_vrvisMYs8A5j7sj8YW1wHhoJSmW&index=9) - Part1 and Part 2 (CMU Multimodal Machine Learning, Fall 2023)]

Reading:
Wojke, N., Bewley, A., & Paulus, D. (2017).  
**Simple Online and Realtime Tracking with a Deep Association Metric.**  
*2017 IEEE International Conference on Image Processing (ICIP).*  
https://doi.org/10.48550/arXiv.1703.07402 \

---
## [Topic 11 Sequential decision making](/Lec11)

### Support or Contact
[Miodrag Bolic email ](mailto:mbolic@site.uottawa.ca)
