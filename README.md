# Sstack
R Package for staircase style stacking of Random Forest Models.

This package aims to provide a simple, effective, method for building Random Forest (RF) models on heterogeneous data types, that is databases where features are missing for a large number of samples. Most notably we focus on data in the following form:
   
   Samples| A |
   
      "   | B | C |
      
           Features
           
This sort of "staircase" structure to data can be stacked in three ways: 

[1] Horizontal (H) stacking -

[2] Vertical (V) stacking -

[3] L shapes (L) stacking - 
