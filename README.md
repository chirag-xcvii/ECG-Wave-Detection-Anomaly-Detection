# ECG-Wave-Detection-Anomaly-Detection

**Problem Statement**

- ECG machines risk warranty nullification with third-party IoT interfaces.
- Limited solutions for patients’ vital signs information extraction.
- ECG machines operate using paper-based systems, lacking digital data capabilities.

**Project Highlight**

- Utilizing camera and computer vision to extract vital information.
- Using the extracted information for better healthcare and assisting medical personnel.

**Project Steps**
- ***YOLO Training & Prediction***: Train YOLO (You Only Look Once) model on annotated ECG monitor dataset for object detection and obtain predictions on all images.
- ***Annotate and Augment Data***: Annotate and augment data using tools like Roboflow to improve model training and performance.
![Data Annotation using Roboflow on 140 ECG Monitor Images (3)](https://github.com/chirag-xcvii/ECG-Wave-Detection-Anomaly-Detection/assets/146003422/43cca9df-e3bf-4c0c-bfdb-61c1f576a7bd)
- ***Cropping with Bounding Box***: Identify and crop regions of interest within the ECG monitor images based on high-probability bounding boxes.
- ***Edge Detection & Boundary Detection***: Apply edge detection techniques to identify wave edges and boundaries within the ECG monitor images.
![Data Annotation using Roboflow on 140 ECG Monitor Images (2)](https://github.com/chirag-xcvii/ECG-Wave-Detection-Anomaly-Detection/assets/146003422/b2657c4c-a061-4078-9753-9ade684ecd77)
- ***Image Transformation***: Transform images from report format to ECG monitor format using rule-based cropping, background removal, and conversion to black and white.
- ***Data Augmentation Pipeline***: Create a pipeline for data augmentation including rotation and cropping to diversify the dataset.
![Data Annotation using Roboflow on 140 ECG Monitor Images (4)](https://github.com/chirag-xcvii/ECG-Wave-Detection-Anomaly-Detection/assets/146003422/8f4b78fb-27f3-46c6-9988-8a20f52de360)
- ***CNN Model Training***: Train a Convolutional Neural Network (CNN) model with specified hyperparameters for normal vs. abnormal classification.
![Data Annotation using Roboflow on 140 ECG Monitor Images (5)](https://github.com/chirag-xcvii/ECG-Wave-Detection-Anomaly-Detection/assets/146003422/f4181bfd-5171-46c7-a984-dccb6e64750a)

**Requirements**

Ensure the following dependencies are installed to run the project:
- Python (3.x)
- TensorFlow
- OpenCV
- NumPy
- Pandas
- Matplotlib




