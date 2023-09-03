# Cost-Sensitive Learning Techniques

Description:

This repository contains the results and analysis of an experiment conducted to evaluate the effectiveness of three different cost-sensitive learning approaches—Minimizing the expected cost, Undersampling, and Weighting—applied to three distinct machine learning algorithms: GaussianNB, LinearSVC, and RandomForestClassifier.

Experiment Highlights:

Minimizing the Expected Cost: This approach showcases significant improvements in the final cost for all three models, with Random Forest Classifier leading the pack with a remarkable 24.4% reduction in method cost. Linear SVC follows closely with an 11.3% reduction, while GaussianNB shows a more modest 4.6% improvement.
Undersampling: The Undersampling approach yields mixed results. It significantly reduces the method cost for Linear SVC (29.3% reduction) and RandomForestClassifier (34.4% reduction). However, it increases the method cost for GaussianNB by a substantial 98.5%, rendering it unsuitable for this algorithm.
Weighting: The Weighting approach demonstrates improvements in the final cost for GaussianNB (20.3% reduction) and Linear SVC (3.4% reduction). However, it leads to a 17.9% increase in the method cost for RandomForestClassifier, making it an unfavorable choice for this algorithm.
Overall Assessment:

The "Minimizing the Expected Cost" approach emerges as the most effective, delivering improved final costs across all three models.
"Undersampling" may prove beneficial for Linear SVC and RandomForestClassifier but is not suitable for GaussianNB.
"Weighting" yields mixed results, offering enhancements for some models while not benefiting others.
Explore this repository to delve into the detailed experiment findings, methodologies, and insights into cost-sensitive learning techniques in machine learning.
