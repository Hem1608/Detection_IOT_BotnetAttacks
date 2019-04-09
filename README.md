Detection_IOT_BotnetAttacks

The aim of the project is to successfully differentiate between benign and malignant data in the data sets to detect the anomalies 
present in the data through anomaly detection method. 
Our evaluations were successfully able to detect malignant data by outlying the anomalies in the data set


The most common infections which targets IOT endpoints are BASHLITE and Mirai Botnets. 
The botnets acquire the access of an IOT endpoint by brute force and the endpoint become a malware itself. 

We extract n features from the arriving packets and we train the data to develop a model to classify the data set. 

1.	Packet-Preprocessing Framework 2. The Feature Extractor 3. The Feature Mapper 4. The core Anomaly Detection Algorithm
The Feature Mapper and the Anomaly Detector runs on two different mode of operation: 1)Train-mode 2) Execution-mode.


