# Optimizing-Support-Vector-Machines-for-Purchase-Prediction
## Details of the project:
In this project, the goal was to analyze the OJ (orange juice) dataset using Support Vector Machines (SVMs) with different kernels. The project focused on predicting purchase behavior based on various predictor variables.

The work began by creating a training set and a test set from the dataset. A support vector classifier was then fitted to the training data using a linear kernel and a cost value of 0.01. The results were summarized, including the number of support vectors for each class.

The training and test error rates were calculated to assess the performance of the linear SVM model. Additionally, the tune() function was utilized to select an optimal cost value, and the process was repeated to compute the training and test error rates using the newly identified cost value.

The same steps were followed for SVM models with radial and polynomial kernels. The training and test error rates were compared, and the optimal cost values were determined for each kernel.

Based on the results, it was observed that the linear SVM approach achieved the lowest error rates, indicating its effectiveness in predicting purchases in the OJ dataset.

Overall, the project aimed to explore and compare different SVM models with varying kernels and cost values, highlighting the approach that yielded the best results in predicting purchase behavior.


