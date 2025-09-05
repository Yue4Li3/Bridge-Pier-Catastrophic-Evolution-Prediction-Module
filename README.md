# Bridge Pier Catastrophic Evolution Prediction Module

This repository provides a simulation and prediction module for **service-life catastrophic evolution of reinforced concrete bridge piers**.  
The module integrates material durability degradation, nonlinear structural performance evolution, and probabilistic reliability analysis.  
The current release provides documentation, with protected source code available as a ZIP package. An open extractable version will be updated later.

---

## 📖 Background

Prefabricated and assembled bridge structures have gained popularity due to their short construction periods, high quality control, and reduced environmental impact.  
However, the **connections between prefabricated components** become critical weak points, where long-term durability and degradation processes require special attention.  

Bridge piers, as key load-bearing elements, are particularly vulnerable:  
- Existing performance evaluation models are often oversimplified.  
- Actual service degradation (e.g., chloride ingress, reinforcement corrosion, stiffness reduction) differs significantly from theoretical assumptions.  

This module provides a more realistic prediction of **catastrophic service evolution** by coupling durability degradation, mechanical performance, and reliability.

---

## ⚙️ Research Methodology

The framework consists of three main stages:

1. **Mesoscopic Chloride Ingress Simulation**  
   - Simulates chloride penetration into reinforced concrete pier sections over a 100-year service life.  
   - Considers random material composition and mesoscopic variability.  
   - Extracts the **time-dependent state of reinforcement corrosion**.  

2. **Finite Element Analysis with Corrosion Effects**  
   - Incorporates the updated state of corroded reinforcement into an FE model.  
   - Modifies critical material and structural parameters to reflect **non-uniform corrosion**.  
   - Simulates nonlinear structural response under different corrosion stages.  

3. **Probabilistic Life-Cycle Prediction**  
   - Trains an **artificial neural network (ANN)** to rapidly approximate the link between durability degradation and mechanical response.  
   - Performs **Monte Carlo simulations (MCS)** to evaluate probabilistic reliability metrics.  

---

## 💡 Module Functions

- Predicts **catastrophic service evolution** of reinforced concrete bridge piers.  
- Simulates **different stages of reinforcement corrosion** and their impact on pier performance.  
- Conducts finite element analysis of **strain distribution and hysteresis response** under progressive degradation.  
- Provides **probabilistic service-life reliability indicators**.  

---

## 🎯 Application Scenarios

- Catastrophic evolution prediction of bridge **pier structures**.  
- Service-life analysis of other prefabricated or cast-in-place components:  
  - Bridge deck slabs under complex loading states  
  - Deck joints  
  - Hinge joints in girder-slab structures  
- Structural design and optimization:  
  - Catastrophe prevention-oriented design  
  - Structural detail optimization for long-term durability  
  - Stochastic catastrophe theory applied to bridge engineering  

---

## 📂 Usage Notes

- Current release provides a **protected ZIP archive** of the source code.  
- The extraction password/code will be shared in a **future update**.  
- Tutorials and demonstration videos will be provided later.  

---

## 📚 References

1. Li Y, Ruan X, Zhang M, et al. *RC structures life-cycle probabilistic evaluation method considering mesoscopic material uncertainty with chloride ingress.*  
   Structure and Infrastructure Engineering, 2022: 1–15.  

---

## 📜 License

This repository follows an **Open Science, Non-Commercial License**:  
- Free for academic and research purposes.  
- Commercial use requires explicit permission from the author.  

---

## 🚧 Status

- 🔒 Code available as protected archive (ZIP).  
- 🛠️ Open extractable code, tutorials, and extended case studies will be updated in later versions.  
