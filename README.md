# State Farm Distracted Driver Detection

![Demo GIF](./assets/distracted_driver_demo.gif)

## About

- Developed a deep learning model using Convolutional Neural Networks (CNN) to detect distracted driving behaviors.
- Fine-tuned an optimized VGG-16 architecture to enhance accuracy and reduce false positives.
- Implemented image augmentation techniques to improve model robustness and generalization.
- Used an ensemble of CNN models to increase detection reliability.
- Achieved validation accuracy exceeding 99.5% on the dataset.

## Project Structure

- `data_preprocessing.ipynb`: Data cleaning, augmentation, and preprocessing for CNN training.
- `cnn_model.ipynb`: Implementation of the CNN model for distracted driver detection.
- `ensemble_model.ipynb`: Application of ensemble modeling techniques for improved accuracy.
- `evaluation_metrics.ipynb`: Performance comparison using accuracy, precision, recall, and F1-score.
- `app.py`: Web-based UI for user-friendly image upload and classification.

## Model Training

- The CNN model was trained on a dataset of driver images labeled with different distraction categories.
- Image augmentation techniques such as rotation, flipping, and contrast adjustment were applied.
- Transfer learning with pre-trained VGG-16 architecture was used to improve feature extraction.
- Evaluation metrics included accuracy, confusion matrix, and classification reports.

## Results and Performance

- The optimized CNN model achieved over 99.5% validation accuracy in classifying distracted driving behaviors.
- Ensemble modeling further improved classification performance.
- The model successfully identified different distraction categories, such as texting, talking on the phone, and eating.

## Web Application

- A user-friendly web app was built for real-time driver distraction detection.
- Users can upload images, and the app classifies the distraction type.
- Developed using Streamlit for interactive visualization.

## Links

- **LinkedIn**: [Kunal Uikey](https://www.linkedin.com/in/kunal-uikey-145086212/)
- **GitHub**: [otakuk11](https://github.com/otakuk11)

## Prediction Example

> **Example: Distracted Driver Detected**

*Detected Behavior: Texting while driving*
```
1. Image captured: Driver holding a mobile phone while looking away from the road.
2. Model confidence: 98.7% - Classified as "Texting while driving."
3. Recommended action: Issue alert and notify relevant authorities if integrated into a real-time system.
```

*Model Prediction Output*  
![Distracted Driver Prediction](./assets/distracted_driver_prediction_graph.png)

