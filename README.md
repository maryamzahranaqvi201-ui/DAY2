## Model Training and Evaluation

Three classification models were trained and evaluated on the cleaned dataset:
-   Support Vector Machine (SVM)
-   Gaussian Naive Bayes
-   Decision Tree

The models were trained on 80% of the data (`X_train`, `y_train`) and evaluated on the remaining 20% (`X_test`, `y_test`). The evaluation metrics used include Accuracy, Precision, Recall, and F1-score, along with Confusion Matrices for visual interpretation of performance.

### SVM Model Performance
**Metrics:**
-   **Accuracy:** 0.9865
-   **Precision:** 0.9828
-   **Recall:** 0.9194
-   **F1 Score:** 0.9500

**Confusion Matrix:**
The SVM model shows a high number of True Negatives (Ham correctly classified as Ham) and True Positives (Spam correctly classified as Spam), with very few False Positives and False Negatives.

### Naive Bayes Model Performance
**Metrics:**
-   **Accuracy:** 0.9718
-   **Precision:** 0.9024
-   **Recall:** 0.8952
-   **F1 Score:** 0.8988

**Confusion Matrix:**
The Naive Bayes model also performs well, though with slightly more misclassifications (False Positives and False Negatives) compared to SVM.

### Decision Tree Model Performance
**Metrics:**
-   **Accuracy:** 0.9696
-   **Precision:** 0.8819
-   **Recall:** 0.9032
-   **F1 Score:** 0.8924

**Confusion Matrix:**
The Decision Tree model exhibits similar performance to Naive Bayes, with a reasonable balance between correctly identifying Ham and Spam messages.

### Conclusion on Model Performance
Overall, the **SVM model demonstrated the best performance** across all metrics, achieving the highest accuracy, precision, recall, and F1-score. This suggests that the SVM model is the most effective among the three for classifying spam messages based on the given numeric features.
Colab paid products
-
Cancel contracts here

M
