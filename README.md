# aws-rekognition-image-labels
Image Labels Generator using AWS Rekognition, S3, and Python

This project demonstrates how to use Amazon Rekognition with an image stored in Amazon S3 to detect objects, scenes, and concepts.  
The results include confidence scores and bounding boxes drawn on the image.

---

Architecture Workflow:
1. Upload an image to an Amazon S3 bucket.
2. Amazon Rekognition analyzes the image and detects labels.
3. A Python script (`detect_labels.py`) fetches the results using boto3.
4. Labels + bounding boxes are displayed using Matplotlib.

---

Setup Instructions

Clone the repository
```bash
git clone https://github.com/<your-username>/aws-rekognition-image-labels.git
cd aws-rekognition-image-labels
