# predicting-cirrhosis-onset-with-python
### Description of the analysis
In this project, we are using a dataset containing Liver Patient from UCI's repository.<br/>

Our prediction task is to determine whether a person needs to be diagnosed for Cirrhosis Based on chemical compounds(bilirubin, albumin, proteins, alkaline phosphatase) present in human body. We are using the input variables that include Age, Gender,TB(Total Bilirubin),DB(Direct Bilirubin),Alkphos(Alkaline Phosphatase),Sgpt(Alamine Aminotransferase),Sgot(Aspartate Aminotransferase) TP(Total Proteins),ALB(Albumin),A/G(Ratio Albumin)and Globulin Ratio Education.<br/>

The important Factor here is recall.<br/>

To conduct our analysis, we will utilize a set of Machine Learning Modules(k-nn, Descision Tree, RandomForest,XGBoost,Neural network, AdaBoost, and gradient boost).<br/>
We are developing a binary classifier to identify if a given person in the datasetneed to be diagnosed for Cirrhosis or not. Our positive case will therefore be Class1(Need's to be diagnosed) and Class0 (Does not need to be diagnosed) will be our negative case.

We will be trying out different models and check if we can develop a model that has sufficient predictive power to accurately
