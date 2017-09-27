We will create the email spam filter model using deep learning and evaluate the model with other currently popular machine learning methods like xgboost, random forest, svm etc.
For this sample project, we will use Enron dataset in English. However this approach works well for other languages also which i had empiricially tested in my job.

This approach is combining unsupervised learning with Supervised learning. We will generate the features in unsupervised way using TF-IDF algorithm and then use this to features to train Models on labeled enron data.

Model trained and evaluated : 

* Deep Learning model trained using keras and tensorflow
* SVM 
* Random Forest
* XGboost

