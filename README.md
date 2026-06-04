Hybrid Network Intrusion Detection & Risk Scoring System
A hybrid machine learning system that detects and classifies network intrusions, assigns risk scores, and flags zero-day threats using the NSL-KDD dataset.
Traditional signature-based intrusion detection systems fail against novel (zero-day) attacks. This project combines supervised and unsupervised ML to detect both known attack types and previously unseen threats in real time.
Approach
Unsupervised (anomaly detection);- Isolation Forest, K-Means Clustering, PCA for dimensionality reduction
Supervised (classification);- Random Forest, XGBoost, Support Vector Machine (SVM), Logistic Regression
Hybrid Decision Engine ;- combines outputs from both layers plus a risk scoring mechanism to produce a final verdict and risk level (Low / Medium / High).
Video: https://youtu.be/sT1Q4vQhJzE
