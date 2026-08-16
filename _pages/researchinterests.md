---
permalink: /researchinterests/
#title: "Research Interests"
author_profile: true
redirect_from: 
  - /md/

---


My research focuses on applying simulation modeling (primarily discrete-event simulation (DES), Markov modeling), operations research methods (probability and statistics, queuing theory), statistical methods (regression modeling), and machine learning (ML) algorithms to analyze and improve complex organ transplantation system and healthcare delivery systems. I also focus on applying network optimization algorithms (A*, Dijkstra's algorithm) to improve routing operations. 


## 1. Organ Allocation Simulation Modeling

### a. Develop a heart allocation simulator
I am working/have worked on the following broad objectives:

- **Develop** a DES model of the heart allocation process from the donors to the recipients
- **Develop** statistical (logistic-regression) and ML frameworks for predicting heart transplant offer acceptances
- **Evaluate** counterfactual heart allocation policies using the DES-based heart simulator and evaluate if any disparity arises within the candidate subgroups

### b. Reuse the existing kidney allocation simulator
- **Evaluate** counterfactual kidney allocation policies using an existing allocation simulator


### c. Develop a Markov modeling approach to analyze the impact of organ banking 
- **Evaluate** impact of organ banking on kidney transplant waitlist dynamics


## 2. Healthcare Delivery Modeling

### a. Patient Diversion Across Healthcare Facility Networks

I am working/have worked on the following broad objectives:

- **Derive** analytical predictors using queuing theory and probability distributions to estimate patient wait time
- **Design** patient diversion algorithms (across healthcare network) that takes into considerations real-time wait estimates
- **Develop** a hybrid analytical queuing theoretic (AQT) and simulation-driven machine learning (*Hybrid Sim-ML*) approach to estimate patient overall length of stay across healthcare facilities
- **Design** facility assignment algorithms that takes into considerations real-time length of stay estimates

We demonstrated the performances of these algorithms via a case study of healthcare facility network in the Indian semi-urban context.


### b. Statistical Modeling of Healthcare-Seeking Behaviour & Referral Pathways

I am working/have worked on the following broad objectives:

- **Develop** cross-sectional surveys for healthcare providers and patients to gather insights into hospital experiences and potential referral mechanisms.
- **Use** logistic regression (binomial and multinomial) to examine healthcare-seeking behavior of patients and analyze how patients and providers navigate referral systems. 

We conducted surveys from different stakeholders at the Indian public healthcare facilities and incorporated their feedback in algorithms developed in **2a**.


## 3. Dynamic route planning

I am working/have worked on the following broad objectives: 

- **Develop** least cost routes for aircraft operating in adversarial or uncertain environments.
- **Apply** graph-based network optimization algorithms such as A* and Dijkstra's algorithm to generate routes in 2-D and 3-D accounting for threats and terrains.

We evaluated the performance of the modified A* algorithms using a synthetic digital terrain elevation dataset.




