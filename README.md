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
