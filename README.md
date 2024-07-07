Q1. Contingency Matrix in Classification
Definition: A contingency matrix (or confusion matrix) is a table that summarizes the performance of a classification model.

Usage: It compares actual outcomes (true labels) with predicted outcomes (predicted labels) across different classes.
Structure: Typically, it is a 
𝐶
×
𝐶
C×C matrix (for 
𝐶
C classes) where each row represents the instances in an actual class and each column represents the instances in a predicted class.
Q2. Pair Confusion Matrix
Difference: A pair confusion matrix focuses on comparing the predicted and actual outcomes for specific pairs of classes rather than all classes.

Usefulness: Useful when interested in understanding the specific performance between two specific classes, especially in multi-class classification problems with imbalanced classes.
Q3. Extrinsic Measure in NLP
Definition: An extrinsic measure evaluates the performance of a language model based on its effectiveness in a specific downstream task.

Usage: It assesses how well the model's predictions contribute to achieving a task's objective (e.g., accuracy of sentiment analysis).
Example: F1-score for named entity recognition or BLEU score for machine translation.
Q4. Intrinsic Measure in ML
Definition: An intrinsic measure evaluates the performance of a model without reference to an external task or objective.

Usage: It assesses the model's performance based on its internal characteristics, such as clustering quality in unsupervised learning.
Example: Silhouette score for clustering or inertia in K-means.
Q5. Purpose of Confusion Matrix
Purpose: It provides a detailed breakdown of a classifier's predictions, highlighting:

True Positives (TP): Correctly predicted positive instances.
True Negatives (TN): Correctly predicted negative instances.
False Positives (FP): Incorrectly predicted as positive (Type I error).
False Negatives (FN): Incorrectly predicted as negative (Type II error).
Strengths: Identifies where the model excels (e.g., high TP, TN) and areas needing improvement (e.g., high FP, FN).
Q6. Intrinsic Measures in Unsupervised Learning
Common Measures:

Silhouette Coefficient: Measures how similar an object is to its own cluster compared to other clusters.
Davies-Bouldin Index: Quantifies the average similarity between clusters, taking into account both separation and compactness.
Interpretation: Higher silhouette scores indicate well-separated clusters, while lower Davies-Bouldin values indicate better clustering.
Q7. Limitations of Accuracy in Classification
Limitations:

Imbalanced Classes: Accuracy can be misleading when classes are imbalanced, favoring the majority class.
Misleading Interpretation: It does not provide insights into specific types of errors (FP vs FN).
Solution: Use additional metrics like precision, recall, F1-score, or ROC curves for a more comprehensive evaluation. Techniques like stratified sampling, class weighting, or resampling can address class imbalance issues.
