# Automated Rock Fracture Detection for Real-Time RQD Estimation

An automated, deep learning-based framework developed to detect rock fractures from core tray images and estimate **Rock Quality Designation (RQD)** for geotechnical engineering applications. 

This project was conducted as part of the **SURGE program at IIT Kanpur** under the mentorship of **Prof. Gaurav Tiwari** (Department of Civil Engineering).

---

## 📌 Project Overview

Manual inspection and logging of rock core samples are time-consuming and prone to human error. This project implements a specialized **Convolutional Neural Network (CNN)** to automate rock fracture detection, categorizing rock fragments to enable precise, real-time RQD estimation.



## 🚀 Key Features & Methodology

### 1. Data Pre-processing & Augmentation
* **Dataset Generation:** Pre-processed and labeled thousands of core tray **Small Square Images (SSIs)** tailored for deep learning architectures.
* **Data Augmentation:** Expanded the original dataset **5x** using robust augmentation pipelines to maximize model generalization across diverse rock types.

### 2. CNN Architecture & Optimization
* **Classification Strategy:** Dual-category classification system distinguishing between two highly distinct fracture types:
  * **Intact**
  * **Non-intact**
* **Training Optimization:** Achieved a **40% reduction in model training time** by optimizing pipeline parameters while maintaining high-fidelity crack detection accuracy.

---

## 📈 Performance & Results

* **RQD Estimation:** Enabled automated, highly accurate estimation of Rock Quality Designation (RQD) for civil and geotechnical analysis.
* **Efficiency Gains:** Delivered an **85% cut in manual inspection time** by streamlining the data processing workflow.
* **High Throughput:** Processes **100+ core tray images per hour**, offering a highly scalable, digital alternative to manual core logging.





