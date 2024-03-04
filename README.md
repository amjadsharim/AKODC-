AKODC: Automatic Knee Osteoarthritis Detection and Classification Using YOLO V4
Overview
AKODC is a software application developed for the automatic detection and classification of Knee Osteoarthritis (KOA) stages using the YOLO V4 object detection algorithm. KOA poses significant health risks if left untreated, and early detection is crucial for effective intervention. Manual analysis of knee X-ray films by physicians and radiologists is time-consuming and subjective, especially in early stages when symptoms are minimal. AKODC aims to address this challenge by automating the detection and classification process, providing a more efficient and objective solution for KOA diagnosis.

Features
Automatic detection and classification of KOA stages using YOLO V4
Real-time processing of grayscale knee X-ray images
Achieves high accuracy and mean Average Precision (mAP) on validation and test datasets
Superior performance compared to state-of-the-art CNN models
Computational efficiency for practical deployment in high-throughput hospital settings
Installation
Clone the repository: git clone <repository_url>
Install dependencies: pip install -r requirements.txt
Usage
Prepare input knee X-ray images in grayscale format.
Run the AKODC software application: python akodc.py --input <path_to_image>
View the detected KOA stages and classification results.
Model Training
The YOLO V4 model used in AKODC was trained on a dataset of 4632 manually annotated knee X-ray images.
Training details and model configuration can be found in the training/ directory.
Evaluation
Evaluation metrics, including mean Average Precision (mAP) and accuracy, are provided in the evaluation/ directory.
Comparative analysis with other CNN models is available for performance assessment.
Contribution
Contributions to AKODC are welcome! If you have any suggestions, bug reports, or feature requests, please submit an issue or a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
Special thanks to the contributors and researchers who provided valuable insights and datasets for the development and evaluation of AKODC.
