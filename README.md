Football Event Detection Models - Offside, Penalty, and Free Kick

This project focuses on training and evaluating three separate models designed to detect key events in football matches: offside, penalty, and free kick. The models were trained using the YOLO (You Only Look Once) architecture for object detection, utilizing data from various sources and performing annotations to ensure high-quality training. The metrics used to evaluate the models include mAP@50, Precision, and Recall.

Data Collection and Model Training

The data for the models was gathered from multiple sources:
 • Roboflow: A dataset containing pre-annotated football-related images.
 • YouTube: Additional footage from real football matches, which was manually annotated for key events like offside, penalties, and free kicks.

The models were trained using the Roboflow 3.0 Object Detection (Fast) model type and evaluated based on the following performance metrics:
 • Mean Average Precision (mAP@50): Measures the accuracy of the model’s predictions.
 • Precision: Represents the accuracy of positive predictions made by the model.
 • Recall: Evaluates the model’s ability to identify all relevant instances of the event.

Model Performance Metrics

Below are the performance metrics for each of the three models:

1. Offside Model
 • mAP@50: 86.1%
 • Precision: 90.5%
 • Recall: 83.1%


2. Penalty Model
 • mAP@50: 72.7%
 • Precision: 73.1%
 • Recall: 75.4%
 

3. Free Kick Model
 • mAP@50: 79.4%
 • Precision: 82.3%
 • Recall: 69.3%
 

Conclusion

The models show promising results, with the offside model performing the best in terms of mAP and Precision, making it highly reliable for detecting offside situations. The penalty and free kick models also provide good results, with room for improvement in Recall and mAP. Overall, these models can be further fine-tuned for better performance in real-world football event detection.
