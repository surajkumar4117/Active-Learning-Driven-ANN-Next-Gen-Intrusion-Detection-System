# **Active-Learning-Driven-Neural-Networks-for-Next-Gen-Intrusion-Detection**
In this project, we developed and evaluated two models for intrusion detection: a Traditional Artificial Neural Network (ANN) and an ANN integrated with Active Learning techniques. The experiments were conducted using the UNSW-NB15 dataset, which comprises contemporary and diverse network traffic records, providing a realistic benchmark for cybersecurity applications.

To address the inherent class imbalance present in the dataset, the Synthetic Minority Over-sampling Technique (SMOTE) was applied. This preprocessing step ensured a more balanced training set, thereby enhancing the robustness and generalization capability of the models.

Our findings demonstrate that the ANN model augmented with Active Learning significantly outperforms the Traditional ANN, achieving an impressive accuracy of 99%. The incorporation of Active Learning allows the model to selectively query the most informative data points for labeling, reducing the amount of labeled data required for effective training. This approach not only decreases annotation costs but also improves the detection precision and recall, making it highly suitable for real-world intrusion detection systems.

Overall, the Active Learning-driven ANN model presents a more efficient and accurate solution for network intrusion detection by combining the strengths of deep learning with intelligent data sampling strategies, thereby advancing the state-of-the-art in cybersecurity defense mechanisms.
