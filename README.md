# Multi-Camera Object Detection Using YOLO

This project presents the results of a multi-camera object detection system powered by a custom-trained YOLO model. The goal was to efficiently run object detection across **three simultaneous video feeds** and showcase the detection accuracy in real-time.

## 🚀 Project Overview

The system performs real-time object detection using three camera inputs processed concurrently. It demonstrates how multithreading can be effectively utilized to handle multiple camera streams while maintaining inference performance. The YOLO model was trained on a custom dataset, specifically annotated to target retail products.

This repository focuses on **visual results only**. No technical implementation or model files are shared here.

## ⚙️ Techniques & Tools

- **YOLO Object Detection**: Custom-trained on a domain-specific dataset.
- **Multithreading**: Ensures simultaneous real-time processing across three video streams.
- **Autodistill for Annotation**: Data annotation and preprocessing were carried out using [Autodistill](https://github.com/MahmoudFarag77/Auto_Labeling_And_Annotation), with the notebook available in a separate repository.

## 📊 Results

Below is a demo GIF showing the detection results from all three cameras:

![Multi-Camera Detection Results](RESULT_1.gif)
![Multi-Camera Detection Results](RESULT_2.gif)
![Multi-Camera Detection Results](RESULT_3.gif)

## 🔗 Related Repository

- [Autodistill fir Auto Labeling and Annotation](https://github.com/MoTawfik11/Auto_Labeling_And_Annotation): Notebook used for automated data labeling and dataset preparation.

---

Feel free to explore the visual results and reach out if you’re curious about the workflow or model performance.
