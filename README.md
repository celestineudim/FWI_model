# FWI Model
The calculation of FWI depends on the statistical point-to-point correlation of four main metrology parameters and five other components based on consecutive daily observations. The daily calculation of FWI might pose some form of limitation to determining fire dangers and implementing necessary fire prevention or early bans in situations where FWI values are very high or extreme. Similarly, the computational cost of ground-based measurements increases significantly with computational parameters.

To respectively solve these problems associated with the conventional calculation of FWI, the objective of the model development is to:
•	Develop a predictive model to forecast FWI by a 1-day lead time,
•	Reduce the parameters (four main ground-based meteorological parameters and six unitless components) required for the calculation of FWI 

These objectives will be achieved by using a Machine Learning algorithm (light gradient-boosting machine (LGBM)) as they can account for system non-linearities with high accuracies

<img width="292" alt="image" src="https://user-images.githubusercontent.com/66778689/206001116-5c771713-b45e-4ed4-99ba-51c20a524e73.png">
