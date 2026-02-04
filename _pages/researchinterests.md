---
permalink: /researchinterests/
#title: "Research Interests"
author_profile: true
redirect_from: 
  - /md/

---


My research focuses on applying simulation modeling (primarily discrete-event simulation (DES))- operations research methods- including probability, statistics, and queueing theory, as well as machine learning (ML) algorithms, to analyze and improve complex service systems. I am currently focused on real-time decision-making in healthcare and in planning routing operations. 



## 1. Organ Allocation Simulation Modeling

### a. Develop organ allocation simulation models from scratch
I am working/have worked on the following broad objectives:

- **Develop** a DES model of the heart allocation process from the donors to the recipients
- **Develop** statistical (logistic-regression) and ML frameworks for predicting heart transplant offer acceptances
- **Evaluate** counterfactual heart allocation policies using the DES-based heart simulator and evaluate if any disparity arises within the candidate subgroups

### b. Reuse the existing organ allocation simulations
- **Evaluate** counterfactual kidney allocation policies using an existing allocation simulator


I use probability and statistical tools to summarize results from the organ allocation simulators, and I am currently integrating trained ML models within the simulator (DES-based) environment. 


## 2. Healthcare Delivery Modeling

### a. Patient Diversion Across Healthcare Facility Networks

I am working/have worked on the following broad objectives:

- **Derive** analytical predictiors using queueing theory and probability distributions to estimate patient wait time
- **Design** patient diversion algorithms (across healthcare network) that takes into consideratios real-time wait estimates
- **Develop** a hybrid analytical queuing theoretic (AQT) and simulation-driven machine learning (*Hybrid Sim-ML*) approach to estimate patient overall length of stay across healthcare facilities
- **Design** facility assignment algorithms that takes into consideratios real-time length of stay estimates

We demonstrated the performances of these algorithms via a case study of healthcare facility network in the Indian semi-urban context.



### b. Statistical Modeling of Healthcare-Seeking Behaviour & Referral Pathways

I am working/have worked on the following broad objectives:

- **Develop** cross-sectional surveys for healthcare providers and patients to gather insights into hospital experiences and potential referral mechanisms.
- **Use** logistic regression (binomial and multinomial) to examine healhcare-seeking behaviour of patients and analyze how patients and providers navigate referral systems. 

We conducted surveys from different stakeholders at the Indian public healthcare facilities and incorporated their feedbacks in algorithms developed in **2a**.


## 3. Dynamic route planning

I am working/have worked on the following broad objectives: 

- **Develop** least cost routes for aircrafts operating in adversarial or uncertain environments.
- **Apply** graph-based network optimization algorithms such as A* and Dijkstra's algorithm to generate routes in 2-D and 3-D accounting for threats and terrains.

We evaluated the performance of the modified A* algorithms using a synthetic digital terrain elevation dataset.




