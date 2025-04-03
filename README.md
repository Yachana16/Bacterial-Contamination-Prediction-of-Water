# Bacterial-Contamination-Prediction-of-Water
Traditional methods for detecting bacterial contamination are often time-consuming and costly,  necessitating the need for advanced computational techniques. This study explores both supervised  and unsupervised machine learning approaches to assess water contamination levels using various  water quality parameters. 
For supervised learning, Random Forest, XGBoost, and Neural Networks were utilized to predict 
bacterial contamination levels. The results demonstrated that the Neural Network model outperformed 
the others, achieving the lowest RMSE (0.2906), lowest MAE (0.2523), and the highest R² score 
(0.0044), indicating its superior ability to capture complex relationships in the dataset. Random Forest 
provided moderate accuracy, while XGBoost underperformed due to sensitivity to hyperparameters 
and potential overfitting. However, the use of randomly assigned contamination labels limits the real
world applicability of the supervised models, underscoring the need for actual contamination data in 
future research. 
For unsupervised learning, clustering and anomaly detection methods were employed to analyze 
contamination patterns without labeled data. K-Means clustering effectively grouped water samples 
based on similarity, DBSCAN identified outliers and non-uniform distributions, and Agglomerative 
Hierarchical Clustering provided a structured contamination hierarchy. The Isolation Forest model 
demonstrated strong anomaly detection capabilities, identifying samples with significant deviations 
from normal conditions. These unsupervised techniques offer valuable insights into water quality 
assessment, especially in scenarios where contamination labels are unavailable.
