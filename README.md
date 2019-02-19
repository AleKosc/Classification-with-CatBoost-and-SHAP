# Classification-with-CatBoost-and-SHAP

In the Jupyter notebook I run through a Kaggele competition dataset, predicting whether or not Amazon employees should automatically get access to their data requests. I have written this from a consulting point of view.

I first outline the requirements, then test out a few models (CatBoost, Random Forest, Logistic Regression) and pick the best one to make predictions. After that evaluate the model results, find the most important features that explain the prediction and even make available the 'reasoning' of individual predictions. This addresses the issue of 'black box' algorithms. CatBoost is not a simple algorithm but using SHAP we can tell why a particular employee has or hasn't been granted access, which important when you need explain such a decision.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleKosc/Classification-with-CatBoost-and-SHAP/master/Images/Screenshot_2019-02-19%20Classification_CatBoost_SHAP.png">
</p>
