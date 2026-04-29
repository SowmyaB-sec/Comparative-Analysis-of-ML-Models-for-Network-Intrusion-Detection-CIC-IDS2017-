# ComparativeAnalysis of ML Models for Network Intrusion Detection (CIC-IDS2017)

 This project benchmarks three Machine Learning models - **Random Forest, Naive Bayes, and Isolation Forest**
- on the **CIC-IDS2017** dataset which contains **2.5M+ labled flows** and **14 attack types** for Network Intrusion Detection.
The goal is to evaluate not only detection performance and accuracy but also **latency, throughput, and scalability** to assess real-world viability.

# Summary of Results
- **Random Forest** achieved the strongest detection performance
    - Accuracy: 99.78%
    - F1-Score: 0.77
- **Naive Bayes** delivered the highest processing speed
    - Throughput: **953k samples/sec**
- **Isolation Forest** provided unsupervised anomaly detection
    - Useful when **labled data is unavailable**

 # Key Insight/Finding
 High accuracy and operational efficiency rarely align/ coexist 
**Model selection should be driven by deployment constraints -  not benchmark scores alove.**

