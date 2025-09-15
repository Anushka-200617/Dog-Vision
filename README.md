Dog Breed Classification using Transfer Learning

Project Overview
This project is a deep learning-based Dog Breed Classification model built using TensorFlow and ResNet50 Transfer Learning.
The model classifies images into 120+ dog breeds using the Kaggle Dog Breed Identification dataset.

Model: ResNet50 (pretrained on ImageNet, fine-tuned for classification)
Dataset: Kaggle Dog Breed Identification
Training Accuracy: ~99%
Validation Accuracy: ~54%
Techniques Used: Transfer Learning, Data Augmentation, Early Stopping, Fine-tuning

Project Structure
dog_vision.ipynb     - Colab notebook with full implementation
README.md            - Project documentation
requirements.txt     - Dependencies

Features
- Transfer Learning with ResNet50
- Image preprocessing and augmentation
- Fine-tuning for improved accuracy
- Early stopping to reduce overfitting
- Accuracy and loss curve visualization

Installation & Usage
1. Clone the repository:
   git clone https://github.com/Anushka-200617/dog-breed-classifier.git
   cd dog-breed-classifier

2. Install dependencies:
   pip install -r requirements.txt

3. Open the Jupyter/Colab notebook:
   jupyter notebook dog_vision.ipynb

Results
Training Accuracy: ~99%
Validation Accuracy: ~54%
Accuracy/Loss curves demonstrate the model performance with and without fine-tuning.

Dataset
You can find the dataset on Kaggle:
https://www.kaggle.com/c/dog-breed-identification

Requirements
tensorflow>=2.9.0
tensorflow-hub
pandas
numpy
scikit-learn
matplotlib

License
This project is open-source and available under the MIT License.

Author
Anushka Wadghule
GitHub: https://github.com/Anushka-200617
LinkedIn: https://www.linkedin.com/in/anushka-wadghule-aa6166300/
