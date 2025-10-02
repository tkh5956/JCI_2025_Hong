# Simulation R Code for *"Multivariate Zero-Inflated Causal Model for Regional Mobility Restriction Effects on Consumer Spending"*

In Section 3 of the manuscript, we conducted simulation studies to evaluate and compare the finite-sample performance of the proposed estimator. The estimating equations described in the paper can be solved using gradient-based root-finding algorithms, such as the `multiroot` function in the R package **rootSolve**. We assess the bias and sample variance of the estimators, using the conventional sandwich variance estimator.  

This repository contains two R scripts for reproducing the simulation results:  
1. **Step1_Simulation.R** – generates data, performs estimation, and saves the result file.  
2. **Step2_Analysis.R** – loads the saved results and produces the tables and figures presented in the manuscript.  

---

## Contact
For questions, please contact:  
**Taekwon Hong**  
📧 taekwon_hong@ncsu.edu | 📧 taecos5956@gmail.com  
---

## Reference
If you use this code, please cite the following article:  

Hong, T., Lu, W., Yang, S., & Ghosh, P. (2025). *Multivariate Zero-Inflated Causal Model for Regional Mobility Restriction Effects on Consumer Spending.* Journal of Causal Inference (Just Accepted).  
