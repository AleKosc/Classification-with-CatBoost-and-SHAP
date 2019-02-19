# Classification with CatBoost and SHAP

In the Jupyter notebook I run through a Kaggle competition dataset, predicting whether or not Amazon employees should automatically get access to their data requests. I have written this from a consulting point of view and you can see the code and explanations in the jupyeter notebook. In order to see all graphs, please use the NBViewer by clicking on the encircled button as shown in the screenshot.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleKosc/Classification-with-CatBoost-and-SHAP/master/Images/NBViewer.PNG">
</p>

I first outline the requirements, then test out a few models (CatBoost, Random Forest, Logistic Regression) and pick the best one to make predictions. I use ROC curves and AUC scores to do that.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleKosc/Classification-with-CatBoost-and-SHAP/master/Images/ROC_Curve.png">
</p>

After that I evaluate the model results and find out where the model went wrong. 

<p align="center">
  <img src="https://raw.githubusercontent.com/AleKosc/Classification-with-CatBoost-and-SHAP/master/Images/Confusion_Matrix.png">
</p>

I then find the most important features that explain the predictions and even make available the 'reasoning' of individual predictions. 

<p align="center">
  <img src="https://raw.githubusercontent.com/AleKosc/Classification-with-CatBoost-and-SHAP/master/Images/SHAP_Overall.png">
</p>

This addresses the issue of 'black box' algorithms. CatBoost is not a simple algorithm but using SHAP we can tell why a particular employee has or hasn't been granted access, which important when you need explain such a decision.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleKosc/Classification-with-CatBoost-and-SHAP/master/Images/Screenshot_2019-02-19%20Classification_CatBoost_SHAP.png">
</p>
