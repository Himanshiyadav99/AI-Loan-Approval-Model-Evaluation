# AI-Loan-Approval-Model-Evaluation
A bank implemented an AI-based loan approval system to automate credit decisions. The model predicts:  Loan Approved (1)  Loan Rejected (0)  Along with a confidence score  The bank deployed three model versions (v1, v2, v3) and now wants to evaluate their effectiveness before full-scale production use.

The bank wants to answer the following critical questions:
Which model version performs best?
Where is the model making mistakes?
Is the model biased toward certain customer groups?
Analyze approval rates and error rates by:
Gender
Age group
Income group
Region
Intersectional segments (e.g., Gender + Income + Region)
Can we trust high-confidence predictions?
Detect high-confidence risky approvals.
Detect unstable model performance across demographic combinations.

Business Risks
If the model is unreliable:
High False Positives → Risky loans approved → Financial losses
High False Negatives → Good customers rejected → Revenue loss
Demographic bias → Regulatory risk & reputational damage
Poor confidence calibration → Misleading decision support

Analytical Approach
The evaluation includes:
Data cleaning and validation
Model performance comparison (Accuracy, Precision, Recall)
Confusion matrix analysis
False Positive Rate (FPR) and False Negative Rate (FNR)
Bias and fairness analysis
Confidence band calibration analysis
Segment-level and intersectional error breakdown

Key Insight
The analysis revealed:
All three models perform close to random (~50% accuracy)
Error rates are consistently high across segments
No extreme demographic bias detected
High-confidence predictions do not significantly improve accuracy
Certain micro-segments show elevated error rates, indicating instability

Final Business Recommendation
The AI model requires:
Performance improvement
Threshold optimization
Probability calibration
Further validation before deployment
The primary issue is low predictive power rather than systemic demographic bias.
