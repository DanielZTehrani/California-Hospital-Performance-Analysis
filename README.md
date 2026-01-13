# California-Hospital-Performance-Analysis
Natural Language Processing analysis of California hospital performance using TF-IDF, logistic regression, and structured clinical variables to evaluate whether narrative hospital text improves quality classification.




# California Hospital Performance Analysis (NLP)
This project applies Natural Language Processing techniques to evaluate whether narrative hospital performance descriptions contain meaningful signals that improve hospital quality classification beyond traditional structured metrics.
Using California hospital data, I transformed free-text performance descriptions into quantitative features and evaluated their predictive value when combined with structured clinical variables.




# Project Overview
- Converted hospital narrative descriptions into TF-IDF features

- Built and compared:
  - Structured-only logistic regression model
  - Combined structured + text-based model
  - Naive Bayes text classifier

- Evaluated model performance across hospital rating categories:
  Below Expected, Meets Expectations, Above Expected



# Methods
- Text Processing: TF-IDF vectorization with stop-word removal  
- Models: Multinomial Logistic Regression, Naive Bayes  
- Structured Features: Complication rates, case volume, risk-adjusted metrics  
- Evaluation Metrics: Accuracy, Recall, F1-score, Class Balance Analysis  



# Key Findings
- Narrative text captures qualitative differences across hospital performance levels
- TF-IDF features improved recall for minority classes
- Structured variables remained strongest for overall accuracy
- Results suggest free-text clinical descriptions add contextual insight, even when not improving raw accuracy



# Tools & Technologies
- Python  
- scikit-learn  
- pandas  
- TF-IDF Vectorization  
- Logistic Regression & Naive Bayes  
