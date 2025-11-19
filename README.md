**Autonomous Visual Recognition in Smart Farming**

Autonomous Visual Recognition in Smart Farming is a machine learning project designed to enhance agricultural productivity by automating fruit condition detection. This system utilizes computer vision to address challenges such as harvesting timing and labor shortages by distinguishing between "Good" (ripe/fresh) and "Bad" (unripe/spoiled) fruits.

This project compares the performance of YOLOv8n, YOLOv8s, and the newer YOLOv11n architectures to determine the most effective model for real-time fruit quality assessment.

📂 Dataset

This project required dataset consists of 5 common fruits found in Malaysia. Images were manually gathered from Kaggle and Google Images and annotated using Roboflow.
- Classes (5): Apple, Jackfruit, Mango, Orange, Strawberry.
- Conditions (2):
  - Good: Ripe, fresh, harvest-ready.
  - Bad: Unripe, spoiled, damaged.
- Total Images: ~200 images (balanced distribution of 20 images per sub-class).
- Preprocessing: Images were resized to 256x256 pixels for training consistency.
- Split: 80% Training / 20% Validation.

***The dataset is not oncluded in this repository***

🛠️ Tech Stack

- Language: Python 3.11+
- Framework: Ultralytics YOLO (v8 and v11)
- Libraries: OpenCV, Matplotlib, Pandas, Seaborn
- Annotation Tool: Roboflow

🚀 Installation

1. Clone the repository
2. Install the required dependencies:
    'pip install ultralytics opencv-python matplotlib pandas seaborn'

📈 Results

The models were evaluated based on Mean Average Precision (mAP), Precision, and Recall. While YOLOv8s performed best initially, YOLOv11n demonstrated superior stability and precision after hyperparameter tuning.

👥 Team

Group D - CSCI 4340 Machine Learning (Semester 2, 2024/2025)
- Galeya Binti Herman Gallego
- Fitrah Nur Humaira Binti Muhammad Radaudin
- Nurfatihah Hamzah

Supervisor: Assoc. Prof. Ts. Dr. Amelia Ritahani Bt. Ismail.

📝 Author

Fitrah Nur Humaira

**This project is for educational purposes.**

