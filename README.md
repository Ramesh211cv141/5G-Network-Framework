**Failure detection framework** for IP core networks in 5G environments.Due to Recent advancements in technology, particularly in the context of 5th-generation mobile networks, demand high-speed and secure internet connectivity. The proliferation of smart devices has led to a significant increase in data generation and network traffic, placing additional stress on networks and devices. To address these challenges, automation has become essential. This study introduces an innovative hybrid feature-selection method designed to detect network and device failures within IP core networks, which are crucial for 5G internet connectivity.

Our  approach involves three key steps:
feature ranking using **Mutual Information (MI)**, **Correlation Coefficient (CC), and Gini Index (GI)**; 
combining the resulting feature sets; and applying the Boruta feature selection algorithm. 

To address data imbalance issues, the **SMOTETomek** method is used. The optimized feature set is then utilized by three popular ensemble approaches (Random Forest, LGBM, and xGBoost) for failure detection.
