# Rock-Classification-Using-Deep-Learning
Rock Classification Using Deep Learning
📌 Project Overview
This project leverages deep learning to classify different types of rocks using Convolutional Neural Networks (CNNs). The model is trained on 505 images spanning four rock categories (Granite, Basalt, Coal, and Andesite) with transfer learning and fine-tuning applied for enhanced accuracy.

📂 Dataset Details
Total Images: 505
Categories:
🪨 Granite – 187 images
🌋 Basalt – 130 images
⛏️ Coal – 85 images
🏔️ Andesite – 103 images
Train/Test Split: 75% training (378 images), 25% testing (127 images)

⚙️ Models & Performance
Model	Accuracy ---- (%)
InceptionResNetV2 | 84.6%
DenseNet201  	    | 90.1%
ConvNeXtTiny	    | 89.0%

🔧 Techniques & Optimization
✔ Transfer Learning & Fine-Tuning
✔ Data Augmentation (Rotation, Scaling, Flipping, etc.)
✔ Batch Normalization & Dropout (0.15–0.35) for Regularization
✔ Feature Scaling for Improved Model Stability
✔ Adam Optimizer & Hyperparameter Tuning for Performance Boost

🛠 Installation & Setup
Ensure you have Python and the required libraries installed:
pip install tensorflow keras numpy matplotlib scikit-learn

Run the Project
1️⃣ Clone the repository
git clone https://github.com/yourusername/rock-classification.git
cd rock-classification

2️⃣ Train the model
python train_model.py

3️⃣ Test the model
python test_model.py

📊 Results & Evaluation
Best Performing Model: DenseNet201 (90.1% accuracy)
Metrics Used: Accuracy, Precision, Recall, F1-score
Visualization: Training performance plotted with loss and accuracy curves

Contributors
👤 Abhay Singh


