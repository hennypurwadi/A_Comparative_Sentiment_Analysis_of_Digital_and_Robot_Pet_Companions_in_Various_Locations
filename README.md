## My Thesis Presentation Video link: https://youtu.be/0GBgFD0WQc8

### RESEARCH QUESTIONS
1. Will the majority of sentiments about digital and robot pet companions be positive or be negative?
2. Does location influence people's sentiments towards digital and robot pet companions?

### ABSTRACT
Compared different machine learning models for sentiment analysis on a labeled dataset with the purpose of finding the best performance model.
Collect an unlabeled Twitter public dataset about digital robot companions from various regions and use the best model with the purpose of finding the most sentiments in the unlabeled dataset. 
Perform a Chi-square test with the purpose of finding dependencies between sentiment and locations.

### Methodology
The methodology for this study will be a combination of approaches, including:
1. An experimental approach for comparing several models' performance and model selection based on the best performance.
2.A quantitative approach for data collection, sentiment analysis, and hypothesis testing.

### PERFORMANCE EVALUATION & MODEL SELECTION
Model                                Accuracy Score

Vicuna LoRA                          0.040

GPT-3 Zero-shot Classifier           0.490

BernoulliNB                          0.769

MultinomialNB                        0.762

Logistic Regression                  0.855

SVM (Support Vector Machine)         0.862

DistilBertForSequenceClassification  0.880

Linear SVC                           0.883

BertForSequenceClassification        0.970


### Result Interpretation
1. Based on the calculated sentiment proportions, all continents have strong positive sentiments. Europe has the highest positive sentiment (63.2%), America (62.6%), Australia (59.1%), and Asia (54.7%).
2. The Chi-Square test supports the null hypothesis of independence.It means that location is not a significant factor in determining which continent is best for AI robot digital companion company marketing.

### This study has several limitations. such as:
1. Tweets are collected without regard to age, gender, ethnicity, or culture.
2. Collect only tweets written in English. This might not represent non-English tweets.
3. Machine learning models include flaws and biases, inaccuracy, and mistakes (e.g., irony, sarcasm, or negation).
4. The sample size of tweets collected from Africa was too small and insufficient to be evaluated.
