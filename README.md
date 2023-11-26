## ML-Model-Interpretability
Overview of model interpretability and popular off-the-shelf methods to use in your own ML frameworks.
The following interpretability methods are reviewed in this code. This is not an exhuastive list, but these are some of the most popular.

1. Model-Based Feature Importance
   
    Gini Importance in Decision Trees/Random Forests
  
    Coefficients in Linear Regression
  
2. Global Surrogate

    Black-Box Random Forest Classifier with Surrogate Decision Tree
  
    Black-Box Neural Network with Surrogate Linear Regression
  
3. Local Interpretable Model-Agnostic Explanations (LIME)

     Paper: https://www.kdd.org/kdd2016/papers/files/rfp0573-ribeiroA.pdf
   
     Github: https://github.com/marcotcr/lime
   
5. Shapley Additive exPlanations (SHAP)

     Paper: https://www.jmlr.org/papers/volume11/strumbelj10a/strumbelj10a.pdf
   
     Github: https://github.com/slundberg/shap#citations
