# 🌿 Enhanced Weed Detection for Cotton Crops using YOLO11 and Soft-NMS  

## 🚀 Project Overview  
This project focuses on **real-time weed detection in cotton crops** using **YOLO11** (You Only Look Once) and **Soft Non-Maximum Suppression (Soft-NMS)** to improve detection accuracy. By leveraging **deep learning and computer vision**, the model effectively identifies and classifies weeds in agricultural fields, enabling **precision farming** and reducing herbicide usage.  

## 📌 Features  
- Utilizes **YOLO11** for fast and accurate weed detection.  
- Implements **Soft-NMS** to enhance bounding box selection and reduce false negatives.  
- Trained on **CottonWeedDet3 dataset** (848 images across 3 weed classes).  
- Achieves **mAP (mean Average Precision) of 0.969**, outperforming YOLOv10.  
- Optimized for **real-time agricultural applications**.  

## 📂 Dataset  
- **Name**: CottonWeedDet3  
- **Weed Classes**: Carpetweed, Morningglory, Palmer Amaranth  
- **Size**: 848 labeled images  
- **Annotations**: YOLO format  

## 📊 Results  
| Metric        | YOLO11 | YOLOv10 |
|--------------|--------|--------|
| Precision    | 0.954  | 0.900  |
| Recall       | 0.886  | 0.851  |
| mAP@0.5      | 0.969  | 0.916  |
| mAP@0.5:0.95 | 0.938  | 0.878  |

## 🖼 Sample Predictions  and results.

### 1️⃣ YOLO11 Weed Detection  
![YOLO11 Weed Detection](https://github.com/savalagikadappa/weed-detection-using-YOLO11/blob/main/YOLO11%20weed%20detection)  

### 2️⃣ Integration of Soft-NMS  
![Integration of Soft-NMS](https://github.com/savalagikadappa/weed-detection-using-YOLO11/blob/main/Integration%20of%20softNMS)  

### 3️⃣ YOLO Workflow  
![YOLO Workflow](https://github.com/savalagikadappa/weed-detection-using-YOLO11/blob/main/YOLO%20workflow)  


## 🚀 Future Improvements  
- Integration of **Dilation-wise Residual Modules (DWR)** for multi-scale feature capture.  
- Addition of **Multi-Scale Modules (MSBlock)** for better context understanding.  
- Deployment on **edge devices for real-time applications**.  
