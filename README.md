👟 Visual Similarity-Based Product Recommendation
This project implements a content-based recommendation system that uses image similarity (via deep learning) to recommend fashion products (shoes, clothes, etc.) based on their visual features. It utilizes ResNet50 for feature extraction and compares product embeddings using Euclidean distance.
🚀 Features
Deep feature extraction using ResNet50 (imagenet pre-trained).

Visual product similarity based on Euclidean distance.

Category-specific recommendations: Men, Women, Boys, and Girls.

Visualization of input and recommended product images.

Easy extendability for streamlit-based deployment.
📊 Sample Output
Displays:

Input product image and title

Top-N visually similar products (based on ResNet features)

🧠 Model Details
CNN Model: ResNet50 (pre-trained on ImageNet)

Feature Shape: Flattened 100352-dim vector

Similarity Metric: Euclidean Distance (via sklearn.pairwise_distances)

📦 Deployment
To deploy this system:

Use Streamlit to build an interactive web interface

Allow users to input a product ID or image

Show visual recommendations and distances
