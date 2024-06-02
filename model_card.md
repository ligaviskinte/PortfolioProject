# Model Card

## Model Description

**Input:** 
The CSE-CIC-IDS2018 dataset, found on Kaggle, is a comprehensive collection of network traffic logs designed for intrusion detection system (IDS) research and development. 

**Output:** 
Type: Categorical. 

Classes:
Benign: Indicates the entry corresponds to normal, expected network traffic.
Malicious: Indicates the log entry reflects a DDoS attack.

**Model Architecture:** 
The model employs the Naive Bayes algorithm, a probabilistic classifier based on Bayes' theorem with a strong assumption of feature independence.
It calculates the probability of a log entry belonging to each class (Benign or Malicious) given the observed features, then selects the class with the highest probability.

## Performance

The primary metric used to evaluate the model's performance is accuracy. Accuracy is calculated as the ratio of correctly classified log entries (both benign and malicious) to the total number of log entries evaluated.


## Limitations

Naive Bayes assumes that features are conditionally independent given the class label. This assumption is often violated in real-world data, particularly in network traffic logs where features can be correlated.

The Categorical features need to be converted into numeric representations, which can introduce limitations depending on the encoding method used.