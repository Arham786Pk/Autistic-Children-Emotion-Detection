🎯 Project: Children's Emotion Detection Using Pre-trained Deep Learning Models
This project focuses on detecting and classifying emotional expressions in facial images of children, with a particular emphasis on supporting autism-related research. It leverages transfer learning by fine-tuning pre-trained deep learning models on a specialized dataset.

🧠 Objective
To evaluate and compare the performance of multiple pre-trained convolutional neural networks (CNNs) in recognizing facial emotions in children, enabling emotion-aware systems useful in healthcare, education, and assistive technologies.

📂 Dataset
Name: Autistic Children Emotions - Dr. Fatma M. Talaat

Description: This dataset contains facial images of autistic children annotated with emotional labels such as happy, sad, surprised, angry, and neutral.

Format: Images are categorized into folders representing each emotion.

Purpose: Designed for emotion detection research, especially for applications involving children with autism spectrum disorder (ASD).

🧹 Preprocessing Overview
Resized all images to match model input size (e.g., 224×224).

Normalized pixel values to [0, 1] for better training performance.

Applied data augmentation techniques (rotation, zoom, flipping) to enhance model generalization.

Split the dataset into training and validation sets.

🧠 Models Used
Five pre-trained CNN models were fine-tuned using transfer learning:

VGG16

DenseNet

MobileNet

Xception

ResNet

All models were trained and evaluated under consistent conditions for fair comparison.

📊 Evaluation
Evaluation metrics included accuracy, loss, confusion matrix, and classification report.

Models were evaluated on a validation dataset.

A comparative bar chart was plotted to showcase model performance.

✅ Results
📌 MobileNet outperformed all other models, achieving the highest accuracy. Its balance between performance and computational efficiency makes it ideal for real-time and edge-based emotion detection systems.

