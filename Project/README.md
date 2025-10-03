# Voice Authentication & Gender Classification System

Designed and implemented a machine learning pipeline for speaker verification and gender identification from raw audio files. The project involved:

*   **Preprocessing & Feature Extraction:** Processed variable-length audio signals, applied noise reduction, and extracted key features including MFCCs, Spectral Centroids, and Zero-Crossing Rate.
*   **Gender Classification:** Built and compared multiple classifiers (e.g., SVM, KNN, MLP) to identify the speaker's gender, ensuring balanced class performance.
*   **Closed-Set Speaker Identification:** Developed a model to verify the identity of a speaker from a known set of individuals, evaluated using metrics like precision, recall, and F1-score.
*   **Clustering Analysis:** Applied unsupervised learning techniques (K-Means, Hierarchical) to explore natural groupings within the voice data and validated the optimal number of clusters using the silhouette score.
