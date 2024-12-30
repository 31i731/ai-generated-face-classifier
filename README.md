# Detecting AI-Generated Faces

This project uses a ResNet50-based classifier to distinguish between AI-generated faces and real faces.

## Key Features
- **Model Architecture**: ResNet50 base model fine-tuned for binary classification.
- **Performance**: Achieved 99% accuracy on the test set.
- **Threshold Tuning**: Improved precision by adjusting decision thresholds.

## Dataset (after clean-up of corrupt samples)
- **Real Faces**: 2201 samples .
- **AI-Generated Faces**: 1000 samples.

## How to Run
1. Clone the repository:
git clone https://github.com/your-username/ai-generated-face-classifier.git

2. Install the required libraries:
pip install -r requirements.txt

3. Run the notebook in Jupyter or Google Colab.

## Results
- Confusion Matrix, ROC Curve, and Classification Report are included.

## Future Directions
- Increase AI-generated samples in the dataset.
- Explore advanced architectures like Xception.
