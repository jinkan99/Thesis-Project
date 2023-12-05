# Thesis-Project
Actual Implementation Code for malicious payload detection in REST API Testing using GMM model

This repository contain different code implementations based on the experiments conducted as part of the project under different conditions. The details for each Experiment is discussed below:

**Experiment 1 - part 1(completed payload is considered to understand the contextual information receieved when complete payload is converted into numerical vectors using tf-idf technique)**
Description: This is the code for 1st part of Experiment 1. In this, threshold is taken as 0.3 to predict annomalies i.e. malicious payloads using GMM model.

**Experiment 1 - part 2(completed payload is considered to understand the contextual information receieved when complete payload is converted into numerical vectors using tf-idf technique)**
Difference: threshold is changed to see the impact of threshold on anomaly prediction
Description: This is the code for 2nd part of Experiment 1. In this, threshold is taken as 0.5 to predict annomalies i.e. malicious payloads using GMM model.

**Experiment 2 - part 1(completed payload is broken down into words or tokens using tokenization technique to perform the word-level analysis on the payload dataset and then converting these words into numerical vectors using tf-idf technique)**
Description: This is the code for 1st part of Experiment 2. In this, threshold is taken as 0.7 and payload dataset is converted to tokens(words) for word-level analysis to predict annomalies i.e. malicious payloads using GMM model.

**Experiment 2 - part 2(completed payload is broken down into words or tokens using tokenization technique to perform the word-level analysis on the payload dataset and refining the words dataset as after breaking down the payloads into words some words of annomalous payload will fall into normal category. And then converting this revised words dataset into numerical vectors using tf-idf technique)**
Difference: words dataset constructed after tokenization technique is refined by carefully updating the labels of words from anom to norm to reduce false negatives.
Description: This is the code for 2nd part of Experiment 2. In this, threshold is taken as 0.7 and payloads dataset in converted to tokens(words) and new words dataset is refined to predict annomalies i.e. malicious payloads correctly using GMM model.
