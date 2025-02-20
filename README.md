### Principal Component Analysis (PCA) and Decision Tree Classification on Wine Dataset
### Overview: 
In this project, we applied Principal Component Analysis (PCA) for dimensionality reduction on the Wine dataset. The process started with manually computing the Eigenvalue Decomposition (EVD), followed by fitting PCA using a standard library, which yielded identical results. Finally, a Decision Tree Classifier was used to predict the classification of a test object based on the reduced features.

### Project Steps:
1. Eigenvalue Decomposition (EVD) Computation:
We manually performed Eigenvalue Decomposition on the covariance matrix of the Wine dataset. This step involved calculating eigenvalues and eigenvectors, which form the foundation for the PCA transformation.

2. PCA Fitting:
After the manual EVD computation, we applied PCA using a standard Python library (e.g., sklearn.decomposition.PCA). The results matched the manually computed eigenvectors and eigenvalues, confirming the accuracy of the PCA implementation.

3. Dimensionality Reduction:
Using the eigenvectors from PCA, the dataset was projected onto the principal components, reducing its dimensionality while preserving as much variance as possible.

4. Decision Tree Classifier:
A Decision Tree Classifier was applied on the reduced features from PCA to classify the data. The classifier was trained on the reduced dataset and used to predict the class of a test object.

5. Outline Prediction:
The trained model was tested with a test object, and the prediction result was obtained, which classified the test object into one of the wine categories based on the reduced features.

### Conclusion: 
By performing manual Eigenvalue Decomposition and fitting PCA, we achieved effective dimensionality reduction on the Wine dataset. The Decision Tree Classifier then used the reduced features for classification. This project demonstrated how PCA can simplify high-dimensional data while maintaining essential information, ultimately enhancing the efficiency of classification model.
