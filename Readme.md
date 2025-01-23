MNIST Classifier | Python, Machine Learning, CNN, Streamlit


Dataset: Utilized the MNIST dataset comprising 70,000 grayscale images (60,000 training and 10,000 testing samples), each of size 28x28 pixels, representing digits from 0 to 9. Performed an 80/20 split on training data for validation, ensuring robust model evaluation.

Performance: Achieved 98% accuracy on the test set using a Convolutional Neural Network (CNN) architecture, delivering highly reliable digit classification with minimal misclassification.

Data Augmentation: Incorporated advanced augmentation techniques such as rotation, scaling, and flipping, leading to a 5% boost in generalization and robustness of the model across diverse variations in digit styles.

Deep Learning Model: Designed a CNN with two convolutional layers followed by max-pooling layers, achieving efficient feature extraction. Fully connected layers and dropout regularization minimized overfitting while ensuring strong generalization to unseen data.

Preprocessing: Normalized pixel values to the [0,1] range for faster convergence, and reshaped inputs into 4D tensors for compatibility with deep learning frameworks.

Visualization: Integrated comprehensive visualizations for data exploration, training progress, and confusion matrices using Matplotlib and Seaborn, facilitating better interpretability of results.

Streamlit Deployment: Deployed the trained model using Streamlit, providing an interactive web-based interface for users to upload handwritten digits and view real-time predictions.

Evaluation: Generated detailed classification reports and confusion matrices to assess model performance, identifying areas for improvement in specific digit classes.

Real-World Use Case: Developed a tool with educational and real-world application potential, such as aiding OCR (Optical Character Recognition) systems and digit-based recognition tasks in academic and professional domains.
