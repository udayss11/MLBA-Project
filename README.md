Malware Detection Using Immunocomputing (CSA–SVM)

This project applies a hybrid Clonal Selection Algorithm (CSA) and Support Vector Machine (SVM) model to detect malware and classify network intrusions. Inspired by the human immune system, the model adapts to evolving cyber threats and improves detection accuracy compared to traditional signature-based methods.

Key Features

CSA used to optimize SVM hyperparameters (kernel, C, gamma)
Achieved 0.97 accuracy with strong performance on DoS and normal traffic
Comparative analysis with CSA–KNN baseline
Includes full preprocessing, EDA, training, and evaluation workflow

Dataset

10,000 network connection records
42 features covering traffic, host behavior, and content attributes
Target classes include: Normal, DoS, Probe, R2L, U2R
