# SmartWaste-AI-3.0-UI
AI-powered waste classification system using CNN, MobileNetV2 and Explainable AI with an interactive Gradio interface.
♻️ SmartWaste AI 3.0

Intelligent Waste Classification System Using CNN, MobileNetV2 and Explainable AI

An AI-powered waste classification system that automatically identifies different types of waste using Deep Learning. The project combines Convolutional Neural Networks (CNN), Transfer Learning with MobileNetV2, and Grad-CAM explainability with an interactive Gradio user interface.

⸻

📌 Project Overview

Waste segregation is an important part of effective waste management. Manual waste classification can be time-consuming and inconsistent.

SmartWaste AI 3.0 addresses this challenge by using computer vision and deep learning to classify waste images into six categories. It also provides visual explanations of model predictions through Grad-CAM and recycling guidance through an interactive web interface.

🎯 Objectives

* Develop an intelligent waste classification system using deep learning.
* Train and evaluate a custom CNN model.
* Improve classification performance using MobileNetV2 transfer learning.
* Apply Grad-CAM to visualize the regions influencing model predictions.
* Build an interactive user interface using Gradio.
* Provide useful recycling recommendations for classified waste.

🗂️ Waste Categories

The system classifies waste into six categories:

Category	Description
Cardboard	Cardboard boxes and packaging
Glass	Glass bottles and containers
Metal	Metal cans and other metal waste
Paper	Paper sheets, newspapers and paper products
Plastic	Plastic bottles and packaging
Trash	General waste that does not fit the other categories

🧠 Models Implemented

1. Custom CNN

A Convolutional Neural Network developed for image classification. It serves as the baseline model for comparison.

2. MobileNetV2

A pretrained MobileNetV2 architecture using transfer learning to improve feature extraction and classification performance.

The model includes:

* Image input resizing to 160 × 160 pixels
* ImageNet pretrained MobileNetV2 weights
* Data augmentation
* Global Average Pooling
* Dropout regularization
* Dense classification layers
* Fine-tuning of selected MobileNetV2 layers

📊 Model Performance

The following are the reported evaluation results from the project experiments.

Model	Test Accuracy
Custom CNN (class-weighted)	72.37%
MobileNetV2	88.68%

MobileNetV2 achieved the best reported test accuracy of 88.68%.

Evaluation metrics include accuracy, precision, recall, F1-score and confusion matrix.

🔍 Explainable AI – Grad-CAM

SmartWaste AI 3.0 integrates Gradient-weighted Class Activation Mapping (Grad-CAM).

Grad-CAM generates a heatmap highlighting image regions that contribute to the model’s prediction. This helps users understand which visual areas influenced the classification.

💻 Interactive User Interface

The project includes an interactive web interface developed using Gradio.

Main features

* Upload an image for waste classification.
* Capture an image using a webcam.
* Display predicted waste category and confidence scores.
* View Grad-CAM heatmap visualizations.
* Receive category-specific recycling guidance.
* View recent classification history during the session.

🛠️ Technologies Used

Technology	Purpose
Python	Programming language
TensorFlow / Keras	Deep learning model development
MobileNetV2	Transfer learning
CNN	Image classification
NumPy	Numerical computation
Matplotlib	Data visualization
Scikit-learn	Model evaluation
OpenCV	Image processing
Gradio	Interactive user interface
Google Colab	Model development and GPU training
GitHub	Version control and project hosting

⚙️ Installation and Setup

Step 1: Clone the repository

git clone https://github.com/smilykarthik914/SmartWaste-AI-3.0.git

Step 2: Open the project directory

cd SmartWaste-AI-3.0

Step 3: Install the required libraries

pip install tensorflow gradio numpy matplotlib scikit-learn opencv-python pillow

Step 4: Open the notebook

Open the project notebook in Google Colab or Jupyter Notebook.

Step 5: Configure the dataset

Download and configure the waste classification dataset, ensuring that the six category folders are available in the expected directory structure used by the notebook.

Step 6: Run the notebook

Execute the notebook cells in order to:

1. Load and preprocess the dataset.
2. Train the custom CNN model.
3. Train and fine-tune MobileNetV2.
4. Evaluate both models.
5. Generate Grad-CAM visualizations.
6. Launch the Gradio interface.

📁 Project Structure

SmartWaste-AI-3.0/
│
├── SmartWaste_AI_3_0_UI_Enhanced.ipynb
├── README.md
├── requirements.txt
│
├── dataset/
│   ├── cardboard/
│   ├── glass/
│   ├── metal/
│   ├── paper/
│   ├── plastic/
│   └── trash/
│
├── screenshots/
│   ├── home.png
│   ├── classification.png
│   └── gradcam.png
│
└── models/
    └── mobilenet_model.keras

Note: The folder structure above describes the intended organization. Dataset files, screenshots and trained model files must be added separately if they are not already included in the repository.

🚀 Future Enhancements

* Deploy the application as a cloud-based web service.
* Develop an Android and iOS application.
* Integrate real-time waste detection using a camera.
* Expand the dataset with additional waste categories.
* Integrate IoT-based smart waste bins.
* Improve model performance using larger and more diverse datasets.
* Add location-based recycling centre recommendations.

👨‍💻 Project Information

Project Name: SmartWaste AI 3.0
Student Name: G Smily
Enrolment Number: 240160226157
Department: Computer Science and Engineering – Artificial Intelligence and Machine Learning
University: GD Goenka University
Project Domain: Neural Networks and Deep Learning

📜 Disclaimer

This project is developed for academic and educational purposes. Model performance may vary depending on image quality, dataset distribution and real-world environmental conditions. Recycling recommendations should be checked against local waste-management guidelines.

⸻

⭐ Acknowledgements

This project uses open-source deep learning frameworks and computer vision technologies, including TensorFlow, Keras, MobileNetV2 and Gradio.

SmartWaste AI 3.0 – Making Waste Classification Smarter Through Artificial Intelligence.
