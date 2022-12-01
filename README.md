# KR_UnilateralTaxPolicy
code for replicating the numerical simulations in Kohl & Richter "Unilateral Tax Policy in the Open Economy"

The Mathematica code can be found in 2 separate files. 

1) "UnilateralTaxPolicy_LogLin_Kohl_Richter"
    - This file serves to compile Figure 1 & Figure 2 in Section 4 of the paper.

3) "UnilateralTaxPolicy_Levels_Kohl_Richter"
    - This file serves to numerically simulate our model in levels. 
      .. Please note: model runs of the different scenarios can take a long time period of several hours on a standard PC. 
      .. Alternative to new runs, the code can be used to read in data from our scenario runs. Data files (.wl) for all scenarios are 
         provided. The storage location might need to be changed in the code, though. (Default setting: "Desktop" on a Windows PC.)
    - It contains code to replicate the results (tables and figures) in 
      .. Section 5 & Appendix A.13 "Social welfare and the optimal tax rate"
      .. Online Supplement S.2 "Trade imbalances"
      .. Online Supplement S.3 "Numerical simulation in levels"
      .. Online Supplement S.6 "Social welfare function based on the Gini coefficient"
