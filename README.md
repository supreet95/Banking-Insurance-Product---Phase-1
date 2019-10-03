# Banking-Insurance-Product---Phase-1
The department of Customer Services and New Products at Commercial Banking Corporation is seeking to predict which customers would buy 
a variable rate annuity product. In this phase of the process, we began variable selection and model building. To proceed, 
we first needed to tackle the concerns of missing variables and linear separation. To correct the four variables with missing observations,
we created a missing category, accounting for each missing value. In the case of the two quasi-separation concerns, 
we condensed the variable categories to ensure the existence of the maximum likelihood estimates.

We began developing our model. Through backward selection, 30% of the original 46 variables were determined to be significant. 
After seeing a model with just the main effects, we tested the relationships between them. We identified some significant interactions, 
which led us to a final model with main effects and interaction terms. As seen in Table 1 below, 
this method produced a hybrid model with 17 significant variables, of which 14 were main effects variables, 
and three were interaction terms.
