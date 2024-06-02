# Datasheet: CSE-CIC-IDS2018


## Motivation

- For what purpose was the dataset created? 
The dataset was created to provide a comprehensive and realistic benchmark dataset for intrusion detection systems (IDS) research and development. It aims to support the training and evaluation of machine learning models for network-based anomaly detection.

- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?
University of New Brunswick

 
## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 
Each instance represents a network flow (connection/session) between devices.
- How many instances of each type are there? 
Approximately 16 million instances across multiple CSV files.
- Is there any missing data?
The dataset may contain missing values in some features, which may require handling during preprocessing.
- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by    doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?
The dataset does not contain personally identifiable information (PII) or other confidential data. 

## Collection process

- How was the data acquired? 
The dataset itself was based on logs of the university's servers, which found various DoS attacks throughout the publicly available period. 
- If the data is a sample of a larger subset, what was the sampling strategy? 
No information available.
- Over what time frame was the data collected?
The dataset spans 10 days.

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 
Network traffic was labeled as benign or malicious, with specific attack types identified for malicious instances.
- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 
The raw PCAP files are not readily available alongside the processed CSV files.
 
## Uses

- What other tasks could the dataset be used for? 
Research on network traffic analysis and security
- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 
The limited set of attack types may not fully reflect the evolving threat landscape.
- Are there tasks for which the dataset should not be used? If so, please provide a description.
The dataset should not be used to develop tools or techniques for malicious activities.

## Distribution

- How has the dataset already been distributed? 
The dataset is publicly available on Kaggle.
- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?  
Attribution 4.0 International (CC BY 4.0)

## Maintenance

- Who maintains the dataset?
University of New Brunswick maintains the dataset.

