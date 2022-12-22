A credit risk dataset was downloaded from Kaggle and then the dataset was cleaned. There were missing data that were filled up and duplicate data were deleted. The categorical data were encoded with OneHotEncoder. Then the dataset was standardized to feed in the k-means clustering. k-means clustering is an unsupervised machine-learning model which tried to classify whether a person will default or not. Then the predicted labels were compared to the exact/actual labels in order to measure model performance. Then I did dimension reduction with PCA and feature selection and then fit the data in the model to check performance and compare with the first k-means model performance. 
Another density-based machine learning model DBScan was used to compare with k-means clustering considering silhouette score. 

![Screenshot_20221222_080722](https://user-images.githubusercontent.com/61625268/209208766-992b1f30-17b2-4068-8084-5d42bc267551.png)

Accuracy measure plot for 3 different scenario. 
