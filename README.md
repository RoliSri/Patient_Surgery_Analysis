# Patient_Surgery_Analysis

We analyzed data to find the surgery type 1 or 0 which has better survival chances for patient. We did all three matching , stratified and weighing and we saw that weighing and stratified were almost same when it comes to balance. Matching did result is loss of data.

Of those three weighting didn’t result in any data loss. Based on these analyses we would suggest that there is likely a negative effect of surgery type 1 on death, which means by taking surgery type 1  the patient is less likely to die but also note that the size/significance of the effect is likely smaller than we found.  We would also suggest that the weighting method is doing the best overall job (reducing covariate imbalance and using all observations).

Weighing(b=0.142  t= 5.09 p < 0.001) as it is having negative effect.

Other covariates which also impacted the surgery type in turn impacted the death counts are p< 0.001

(Intercept)           -0.19951    -9.221  

factor(surgerytype)1   0.14179     5.094 

bloodpressure         -0.05575    -3.921 

temperature           -0.07955    -5.690 

creatinelevels         0.04553     2.836  

kg                    -0.03087    -2.138    

cognitivedecline       0.23898     5.605 

cancer                 0.39961     13.395  

transferedin          -0.12606    -2.722  

nolifesupportorder     0.44069     12.995  

trauma                -0.56678    -4.091 

