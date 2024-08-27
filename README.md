# Optimizing 5G Network Slices: LSTM and Game Theory Synergy

# Overview
This repository contains the code and research paper for the work titled "Optimizing 5G Network Slices: LSTM and Game Theory Synergy". The project proposes a new approach to optimizing efficiency in resource utilization witth LSTM playing traffic prediction and forecasting role while Game theory focuses on optimizing the resources given the predictions. 

# Abstract
Advancements in fifth generation (5G) technology have seen a rise in adapting network slicing (NS) to differentiate the services offered in different network segments due to dif- ferences in performance requirements and traffic characteristics. With the growing demand for network automation, several works have explored the concepts of intelligent network slicing. This work, however, demonstrates an approach to traffic prediction that informs network function (NF) resource demands based on the traffic pattern studied in the network slices (NSs). Using traffic volume as the basis for sharing resources among NFs in the NSs, Long Short-Term Memory (LSTM) algorithm is used to study and predict the traffic patterns. This prediction is then used as input to the resources allocation algorithm, that is based on game theory, where the resources are allocated dynamically and fairly amongst the NSs. The work demonstrates a foundation on which all other resources allocation–in the Radio Access Network (RAN), Transport Network (TN), and Core Network (CN)–can be based on to formulate strategic resource sharing amongst NFs.

# Contents
Code: The source code used to implement develop the concept and test it.
Paper: The full research paper detailing the methodological approaches and results.


# Features
Cellular network traffic data simulation 5G (eMBB, URLLC, mMTC)
Cellular network traffic prediction/forecasting with LSTM
Network resources allocation and optimization using Game Theory

# Requirements
Requirements
Python 3.12+
TensorFlow
Keras
NumPy
Scikit-learn
Matplotlib

# Results
The resources allocations detailing NF placement in the SCs defining the NSs, and as orchestrated by the current NFV and approaches show a promising direction towards automated physical and network resources utilizations by emonstrating the allocation/distribution of two resources available for the NSs. The first is the bandwidth, which is necessary for the transmission of packets to and from the NFs running in the NSs, and the second is the memory, which is at the core of information processing of the NFs. In this regard, it is necessary to note that the NFs run in the servers. And, while the NFs capacities are always defined at their deployment, and the requirements are pre- configured, it is in the 5G and beyond vision that the NFs should utilize only the resources they require. For this reason, the presence of a single cluster of servers that hosts the NFs with imaginary 1GB of memory and a network interface configured with 1Gbps of bandwidth is assumed.

# Future Work
The work herein requires that it is deployed in a test bed or a real network. To do this, one requires to consider the intricacies of traffic traversing the network, thereby implementing the required network protocols in gathering and processing the data. Furthermore, depending on the deployment and how the networks are run, it is necessary to develop a universal framework for automated NF placement, in this case considering the capacity requirements that impact the QoS. 

# Ongoing 
This work has been submitted for revision in IEEE CCNC 2025 Conference.

<!-- # Citation
Emmanuel J Samson, Kamrul Hasan, Liang Hong, Sachin Shetty, Imtiaz Ahmed, Henry Onyeka (2024). Enhancing UAV Security Through Zero Trust Architecture: An Advanced Deep Learning and Explainable AI Analysis. 2024 Workshop on Computing, Networking and Communications (CNC), IEEE. -->


# Contact
For questions or collaborations, please contact:

Emmanuel Samson - esamson@tnstate.edu
Kamrul Hasan - mhasan1@tnstate.edu
