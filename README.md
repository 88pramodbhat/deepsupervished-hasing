My project is titled **Deep Supervised Hashing for Content-Based Image Retrieval using an Adaptive Attention-Guided Multi-Level Deep Supervised Hashing framework.**

The main objective of this project is to retrieve visually and semantically similar images from a large image database efficiently.

Traditional image retrieval systems often rely on comparing image features directly. However, searching through large collections of images can be computationally expensive and time-consuming.

To address this problem, we developed a deep supervised hashing approach.

In our project, we used the **ResNet-50 architecture** as the backbone for extracting visual features from images. We used the **NUS-WIDE dataset**, which contains images with associated semantic labels.

The extracted features are passed through our attention-guided multi-level hashing framework. The framework learns compact binary hash codes that represent the semantic information of images.

During image retrieval, we compare the hash codes of the query image with those stored in the database using Hamming distance. Images with smaller Hamming distances are considered more similar and are retrieved first.

We evaluate the retrieval performance using metrics such as **Average Precision at 50 (AP@50)** and **Precision at 10 (Precision@10)**.

The main advantage of this approach is that binary hash codes require less storage and allow efficient similarity searching compared with directly comparing high-dimensional image features.

Through this project, I gained knowledge of deep learning, CNN architectures, feature extraction, attention mechanisms, hashing techniques and image retrieval.
