Youtube URL: https://youtu.be/R7i7f67W_rA
Abstract:
Given the variety of available Machine Learning (ML) models and the importance of evaluating their performance, the purpose of this report is to investigate and compare various ML algorithms such as Linear Regression, Ridge, Lasso, Decision Tree, Kernel Trick, Bagging (Bootstrap Aggregating), and AdaBoost to train a predictive model to estimate the alcohol content of white wine. The study will conduct a thorough comparative analysis of these models to identify the best one for predicting white wine alcohol content.

Literature Review:
In recent years the demand for machine learning (ML) in the wine industry has been growing(Gonzalez Viejo & Fuentes, 2022). The main purpose of ML is to predict a certain target value (Regression) or a class (Classification) based on the provided features. Many studies have focused on various methods and algorithms in ML to evaluate the optimum model for the prediction (Mor et al., 2022). For example, (Bhardwaj et al., 2022) employed various machine learning algorithms such as Support Vector Machine (SVM), Random Forest (RF), Decision Tree Classifier (DTC), Gaussian Naive Bayes (GNB), XGB, K closest neighbour (KNN), Adaptive Boosting (AdaBoost), and the Stochastic Gradient Decision Classifier (SGDC) to predict wine quality. The main finding of the study was that the use of synthetic data generation and feature selection before machine learning analysis can be effective in predicting the quality of New Zealand Pinot Noir wines. The authors introduced the RF and AdaBoost models as machine learning classifiers to predict wine quality and evaluated their performance based on accuracy, precision, recall, F1 scores, and the ROC-AUC score. According to the results, AdaBoost predicted wine quality with higher accuracy without feature selection, with feature selection (XGB), and with essential variables. Overall, the performance of all classifiers (except KNN) improved when the model was trained and tested using essential variables. Similarly, (Dahal et al., 2021) utilized Ridge Regression, Support Vector Machine, Gradient Boosting Regressor, and multi-layer Artificial Neural Network to predict wine quality based on various parameters. This study shows that Gradient Boosting Regressor (GBR) outperforms all other models with MSE, R, and MAPE of 0.3741, 0.6057, and 0.0873 respectively. The study also demonstrates how statistical analysis can be used to identify the components that mainly control the wine quality before production. Also, (Mahima et al., 2020) studied the use of machine learning algorithms such as random forest algorithm and K-nearest neighbour (KNN) to analyze the quality of wine. They used a large dataset of chemical information on 6499 types of Portugal wines, of which 4989 varieties are of white wines and 1650 varieties are of red wines. These datasets contain 1599 observations with 12 different feature variables/attributes such as alcohols, residual sugar, chloride, density, free sulphur dioxide, total sulphur dioxide and pH present in both red and white wines. The study concluded that the quality of wine can be predicted with a precision of 90-92% using KNN, random forests, and support vector machines. Also, found that the concentration of alcohol is the most important parameter for wine quality. The authors used a decision tree to classify the quality of wine, but it only classified quality values ranging from 4 to 7 and did not classify extreme quality values, i.e. 0-3 and 7-10. Regression trees among other machine learning algorithms provided the best result with more accuracy. Moreover, Shaw et al., (2020) studied wine verification and quality analysis using data mining tools and different classification algorithms. They used a dataset of 4898 instances of red wine from the UCI machine learning repository and analyzed the physical and chemical variables that influence the quality of wines. They applied more than one ML algorithm to predict the quality of the wine, namely SVM, random forest, and multilayer perceptron. This study concluded that the random forest algorithm gave the best result with an accuracy percentage of 81.96, followed by the multilayer perceptron algorithm with an accuracy percentage of 78.78, and lastly, the support vector machine algorithm with an accuracy percentage of 57.29. The authors also explained that the randomness of the random forest algorithm helped to increase the overall model's accuracy. 

A limited review of the literature shows that there are many models available for utilization in machine learning training and an evaluation of the performances of these models is a necessary task. Hence, this report studies various machine learning algorithms such as Linnear Regression, Ridge, Lasso, Decision Tree, Kernel Trick, Bagging (Bootstrap Aggregating) and AdaBoost to train a model to predict the alcohol content of white wine. A comparison study between these models will be conducted to develop the best model. 


References:
Bhardwaj, P., Tiwari, P., Olejar, K., Parr, W., & Kulasiri, D. (2022). A machine learning application in wine quality prediction. Machine Learning with Applications, 8, 100261. https://doi.org/10.1016/j.mlwa.2022.100261
Dahal, K. R., Dahal, J. N., Banjade, H., & Gaire, S. (2021). Prediction of Wine Quality Using Machine Learning Algorithms. Open Journal of Statistics, 11(02), 278–289. https://doi.org/10.4236/ojs.2021.112015
Gonzalez Viejo, C., & Fuentes, S. (2022). Digital Assessment and Classification of Wine Faults Using a Low-Cost Electronic Nose, Near-Infrared Spectroscopy and Machine Learning Modelling. Sensors, 22(6), 2303. https://doi.org/10.3390/s22062303
Mahima, Gupta, U., Patidar, Y., Agarwal, A., & Singh, K. P. (2020). Wine Quality Analysis Using Machine Learning Algorithms (pp. 11–18). https://doi.org/10.1007/978-981-15-2329-8_2
Mor, N. S., Asras, T., Gal, E., Demasia, T., Tarab, E., Ezekiel, N., Nikapros, O., Semimufar, O., Gladky, E., Karpenko, M., Sason, D., Maslov, D., & Mor, O. (2022). Wine quality and type prediction from physicochemical properties using neural networks for machine learning: a free software for winemakers and customers. AgriRxiv, 2022. https://doi.org/10.31220/agriRxiv.2022.00125
Shaw, B., Suman, A. K., & Chakraborty, B. (2020). Wine Quality Analysis Using Machine Learning (pp. 239–247). https://doi.org/10.1007/978-981-13-7403-6_23
 
