# Hybrid-Fashion-Recommendation-System-using-Deep-Learning

**Overview**
This project explores visual similarity in a fashion product dataset using hybrid image embeddings from pre-trained deep learning models. It integrates ResNet, VGG, and Inception models for enhanced feature extraction, offering a rich embedding framework that captures nuanced visual characteristics. With cosine similarity, it ranks and recommends similar items based on visual attributes, assisting with applications like visual search and product recommendations.

**Key Objectives**
* **Feature Extraction:** Leverage ResNet, VGG, and Inception for robust, hybrid embeddings.
* **Similarity Computation:** Calculate image similarity using cosine similarity on embeddings.
* **Product Recommendation:** Build a recommendation system to suggest visually similar products.

**Model Development**
* **Hybrid Embedding Generation:** For each image, embeddings from ResNet, VGG, and Inception are extracted and concatenated, forming a unique vector that represents its visual features.
* **Similarity Analysis:** A similarity matrix is constructed using cosine similarity between embeddings, allowing efficient comparison across images.
* **Image Recommendations:** Retrieve and display similar items for any selected product using a similarity-based retrieval system.

**Tools and Libraries**
* **Kaggle & KaggleHub:** For dataset access and management.
* **PyTorch & torchvision:** For deep learning model integration and feature extraction.
* **swifter & joblib:** To accelerate computations and save embeddings for efficient recommendation.

This structured approach enables effective image-based recommendations, enhancing user experience in visual-based fashion search applications.
