---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

![Tales Imbiriba](/figs/Photo_Imbiriba.jpg){: width="130" : style="float: right" } 
Tales Imbiriba is an Assistant Research Professor in the Department of Electrical and Computer Engineering (ECE) and a Senior Research Scientist at the Institute for Experiential AI, both at Northeastern University (NU) in Boston, MA, USA. He earned his Doctorate degree from the Department of Electrical Engineering (DEE) at the Federal University of Santa Catarina (UFSC) in Florianopolis, Brazil, in 2016. Following that, he worked as a Postdoctoral Researcher at the DEE–UFSC from 2017 to 2019 and at the ECE department of NU from 2019 to 2021. His research focuses on Bayesian inference, online learning, and physics-guided machine learning, with applications in *human-centered technologies*, *remote sensing of the environment*, and *enhanced security technologies*.

<!-- Tales Imbiriba is an Assistant Research Professor at the ECE dept., and Senior Research Scientist at the Institute for Experiential AI, both at Northeastern University (NU), Boston, MA, USA. He received his Doctorate degree from the Department of Electrical Engineering (DEE) of the Federal University of Santa Catarina (UFSC), Florianopolis, Brazil, in 2016. He served as a Postdoctoral Researcher at the DEE--UFSC (2017--2019) and at the ECE dept. of the NU (2019--2021). His research interests concentrate on Bayesian inference, online learning, and physics-guided machine learning with applications to *human-centered technologies*, *remote sensing of the environment* and *technologies for enhanced security*. -->


<!-- ________________________ -->
## Research:


### *Statistical Machine Learning*

**Physics-guided machine learning:**
![ASD](/figs/APBM.png){: width="250" : style="float: right" }
My research is rooted in statistical modeling and inference applied to different problems where estimating physical latent quantities is paramount. Retrieving such quantities becomes even more challenging in unsupervised scenarios where the physical significance of latent variables can be imposed through modeling design. In this context, my research focused on the design of statistical models and inference strategies capable of capturing the physical significance of estimated states by using either: physics-based models, regularized hybrid physics-based data-driven models, or by enforcing constraints and regularizations. I also devoted much attention to time-series analysis which requires dynamical modeling of latent quantities. In this context, I have addressed both first-principle modeling and hybrid data-driven first-principle designs considering either online and offline learning scenarios.
<!-- Fig.~\ref{fig:apbm} depicts the \textit{augmented physics-based model} (APBM) which I proposed for online learning in~\cite{Imbiriba_hybrid_2022, Imbiriba_apbm_taes_2023} and leveraged in~\cite{Borsoi_DKFUnmix_2023} and~\cite{nardin2022jamming, Nardin_jammingloc_perform_apbm_2023, Wu_fedjammerclass_plans_2023} in offline learning contexts. -->

*Related Publications:* [FUSION2022](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9841291)
  [TAE2023](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10302385)  [TIP2023](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10103834)



**Online machine learning and RBE:**
![ASD](/figs/Lorentz.png){: width="250" : style="float: right" }
 The dynamic nature of many problems demands data analysis strategies capable of adapting to different conditions, i.e., non-stationary environments, which are expressed by changes in data statistics over time and space. In this context, adaptive and recursive Bayesian estimation (RBE) strategies play a relevant role in linear and nonlinear data analysis.
 Insights from these fundamental adaptive methodologies resulted in my contributions for multi-temporal hyperspectral image analysis, performance analysis of a decision-theory-based framework for echo canceler control using adaptive filters, online inference of neural network (NN) and Gaussian process (GP) models in the context of indoor navigation. 
 ![ASD](/figs/NODA.png){: width="240" : style="float: right" }
 At the same time, I developed new works in the context of particle filtering. 
Recently, I focused on data-driven *augmented physical-based models* (APBMs). Unlike other physics-related neural network approaches, APBMs act as correcting terms, or nonlinear fluctuations, around the physical model. We empirically demonstrated that if properly controlled, such models can maintain the physical meaning of latent states learned in an unsupervised fashion. One point of my current research is to improve learning mechanisms and understand the explainability of APBMs. 
Following another trend of approximation methods for PDEs, we provided an unified framework for estimation and data assimilation for Neural Operators (NOs). Our work, proposed a seemless update approach for NOs, capable of improving estimations of standard NOs by assimilating sparsely availble data.

*Selected Publications:* 
[ICLR2024](https://arxiv.org/pdf/2402.15656.pdf)
[FUSION2022](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9841291)
  [TAE2023](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10302385) 



### *Human-centered Technologies for Health and Wellbeing*



**Automated aggression prediction in youth with autism spectrum disorder (ASD):** ASD is an increasingly Biosensor Data prevalent childhood disorder associated 
![ASD](/figs/ASD.png){: width="310" : style="float: right" }
with high healthcare costs. One of the most frequently observed problem behaviors in youth with ASD is aggression (often occurring without warning) which is a primary cause for referral to behavioral healthcare services. Automated aggression prediction can be posed as a time-series classification problem where one wishes to predict future aggression episodes based on biosignals captured from wearable sensors.

*Check out our JAMA paper:*
[Wearable Biosensing to Predict Imminent Aggressive Behavior in Psychiatric Inpatient Youths With Autism](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2813185)


**BLADDER. Biomechanistic Modeling with Deep Differential Equations (BLADDER):**
![ASD](/figs/BLADDERFlowchart.jpg){: width="310" : style="float: right" } 
BLADDER is a research initiative where I leverage hybrid first-principle data-driven models for modeling physiological systems such as the lower urinary tract. This topic is closely related to the fundamental topics of my research which aim at constructing hybrid approaches and (online and offline) learning strategies for complementing the known mechanistic models. A major challenge in BLADDER relates to the physical interpretation of latent states posing challenges over the inference process and observability (in the control theory sense) of such quantities. 
Recently we proposed a 
*Recursive Neural Ordinary Differential Equation*(RNODE) approach for partially measured systems which leverages a modified Newton formulation of recursive state-space optimization that mitigates parameter estimation issues of distinguishable partially measured systems. 
<!-- Fig.~\ref{fig:hh_result} presents the state integration over time after learning the hybrid first-principle-NN model using RODE and competing methods over well-understood Hodgkin-Huxley Neuron systems.  -->

*Related Publications:*
[EMBC21](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9631038&casa_token=nvBg55L7fcQAAAAA:uK-35EWoAZqUsFUuaMGe5s5nVb1_le84LKm_6Zy1FOY8Pd93G7Gw7eC_LePuO17tP0pE7de_1j8&tag=1)
[FUSION2022](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9841291)

**Active learning for motor cortex mapping:**
![TMAP](/figs/TMSMap.png){: width="310" : style="float: right" } 
Transcranial magnetic stimulation (TMS) application can map cortical motor topography by spatially sampling the motor cortex and recording motor-evoked potentials (MEP) with surface electromyography. 
Recently, I designed novel active learning methods to automatically infer optimal future stimulus loci in place of user expertise. Specifically, we proposed an active GP strategy with loci selection criteria based on entropy, mutual information (MI), and sampling strategies inspired by our latest developments in the context of particle filters.

*Related Publications:* [TNSRE2021](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9515996) [PETRA2020](https://dl.acm.org/doi/abs/10.1145/3389189.3389202) [FUSION2020](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9190631) 

### *Remote sensing and multispectral imaging for environmental monitoring and sustainability*

**Spectral Unmixing for Hyperspectral Imaging:**
Spectral Unmixing (SU)  consists of identifying the spectral signature of target materials (endmembers) and estimating their proportions (abundances) in a given scene. This problem connects many fields in signal processing and machine learning such as inverse problems, blind source separation, matrix and tensor factorization, neural networks, and kernel methods. My research on this topic started during my Ph.D. (2012--2016) and focuses on four specific problems: nonlinear SU, SU accounting for endmember variability, regularization strategies for SU, and multi-temporal SU. 

*Selected Publications:* [TCI2023](https://arxiv.org/pdf/2310.02340) [TIP2023](https://arxiv.org/pdf/2303.10566) [GSRSMagazine2021](https://arxiv.org/pdf/2001.07307.pdf) [TIP2016](https://arxiv.org/pdf/1503.05521.pdf) [ICASSP2018](https://arxiv.org/pdf/1710.07723) [TGRS2019](https://arxiv.org/pdf/1811.02413.pdf) [TIP2019](https://arxiv.org/pdf/1808.10072.pdf) 


**Water Mapping:** Satellite imaging is central to monitoring the intensity of critical natural phenomena. One crucial feature of satellite images is the trade-off between spatial/spectral resolution and their revisiting time. We focused on fusing multi-temporal, multi-spectral images acquired from different instruments with different spatial resolutions, generating high-resolution estimated image sequences at higher revisiting rates. To achieve this goal, I formulated the fusion method as a recursive state estimation problem. I studied its performance in filtering and smoothing contexts, connecting it with my adaptive machine-learning interests. Despite the more general impact of multitemporal fusion, these images are used to provide more accurate water maps. I also employed a recursive Bayesian classification strategy to classify multi-temporal multispectral satellite images with a focus on water mapping. This work was partially funded by the National Geographic Society. 

*Related Publications:*   [ISPRS_UnderReview](https://arxiv.org/pdf/2301.01796.pdf)   [ISPRS2022](https://arxiv.org/pdf/2301.02598)   [AERO2022](https://arxiv.org/pdf/2204.12566)

**Macro-plastic detection in water bodies:**
![TMAP](/figs/PlasticClassification.png){: width="310" : style="float: right" } 
Recently, I analyzed the impact of using hyperspectral data for classifying plastic debris in water bodies and generated promising results compared to usual RGB images. Currently, I am writing a grant proposal on the topic where I aim to develop the methodology for estimating the flow of macroplastics on rivers using snapshot hyperspectral imaging sensors.

*Publications:* [WHISPERS2023](https://arxiv.org/pdf/2307.12145.pdf)

### *Technologies for enhanced security*

**Distributed AI for enhanced security in satellite-aided wireless navigation (RESILIENT):**
![TMAP](/figs/Resilient.png){: width="310" : style="float: right" } 
I recently used APBMs for modeling and tracking malicious radio-frequency (RF) signals capable of disrupting GNSS services. We also proposed a federated learning approach to perform RF field estimation. Recently, I was awarded (November 2023) an NSF-AoF-CIF small grant on the topic where my role is **Co-PI**. 
The total grant amount is \$1.2M from which my share is 25%. In this project our goals are: *(i)* local threat detection; *(ii)* distributed privacy-aware threat localization; and *(iii)* robust collaborative positioning using threats as 'information sources'.

*Selected Publications:* [ICASSP2023](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10095731) [PLANS2023](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10140023) [PLANS2023-Fed](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10140124)


**Cognitive Radar Networks (DoD):** 
![RBTargetRecognition](/figs/RBTargetRecognition.png){: width="310" : style="float: right" }
I am a co-investigator in three Department of Defense (DoD) funded research topics involving Northeastern University, Kosta's Research Institute, and Army Research Labs (ARL). In the projects I am developing strategies to *(i)* mitigate Jamming and spoofing of radars; *(ii)*  perform behavioral recognition and analysis in the context of adversarial distributed radar networks; *(iii)* target recognition using radar networks. In these projects, the methodology I am developing heavily relies on statistical modeling, recursive Bayesian frameworks, online learning, and recursive classification approaches. 
In *(i)*, I am developing robust methodologies for target detection under different jamming procedures. In *(ii)*, I am developing an online inverse Bayesian inference approach for learning the radar network behavior and goals. In *(iii)*, I am developing a distributed recursive radar cross-section (RCS) classification approach for target recognition. 

*Related Publications:* [TAEUnderReview2024](https://arxiv.org/pdf/2402.17987.pdf)