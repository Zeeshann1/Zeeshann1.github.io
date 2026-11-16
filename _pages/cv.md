---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


## PROFESSIONAL SUMMARY

AI/ML Engineer with over four years of professional experience developing and deploying deep learning solutions for real-world applications. Specialized in Computer Vision, including object detection, image segmentation, industrial defect inspection, image matting, OCR, and visual behavior recognition.

Experienced across the end-to-end machine learning lifecycle, including dataset development, model training, evaluation, error analysis, optimization, and Edge AI deployment. Hands-on experience with LLMs, vision-language models (VLMs), retrieval-augmented generation (RAG), and LangChain-based applications for document, image, and video understanding.

Strong interest in building scalable, reliable, and production-ready AI systems, including intelligent agents and multimodal AI applications.

## TECHNICAL SKILLS

**Computer Vision & Deep Learning:** Object detection, image segmentation, industrial defect detection and visual inspection, anomaly detection and heatmap generation, image matting, OCR, foundation models (SAM3, DINOv3), model fine-tuning, quantitative evaluation, error analysis, and model optimization.

**LLMs, VLMs & Generative AI:** Large Language Models (LLMs), Vision-Language Models (VLMs), Retrieval-Augmented Generation (RAG), LangChain, agentic workflows, prompt engineering, and multimodal document, image, and video understanding.

**Frameworks & Libraries:** PyTorch, TensorFlow, ONNX, Detectron2, YOLO, OpenCV, NumPy, Pandas, and Scikit-learn.

**Image Processing & Data Engineering:** Image preprocessing and postprocessing, mask refinement, morphological operations, dataset curation, data augmentation, annotation workflows, and model-assisted auto-labeling.

**Model Deployment & Edge AI:** ONNX, TensorFlow Lite, RKNN Toolkit, model conversion and quantization, inference optimization, and deployment on Rockchip RK3588/RK3399 platforms and Raspberry Pi.

**Development Tools & Platforms:** Linux, Git, Jupyter Notebook, GPU training environments, X-AnyLabeling, and Streamlit.

**Programming Languages:** Python, C++, MATLAB.

## EDUCATION

### MS, Electronics and Communication Engineering
**Shanghai Jiao Tong University (SJTU)** | Shanghai, China  
2018 – 2020

Thesis: *Improved Wi-Fi Indoor Localization Based on Signal Quality Parameters and RSSI Smoothing Algorithm.*

### B.E., Electrical Electronics Engineering
**Sukkur IBA University (IBA)** | Sindh, Pakistan  
2013 – 2017

Thesis: *Green Wireless Capsule Endoscopy Battery-Friendly Algorithm Based on Digital Signal Processing.*

## PROFESSIONAL EXPERIENCE

### Software Engineer (AI & ML)
**Apple Inc. (Contractor via Metron HK)** | Shanghai, China  
April 2025 – September 2026

- Developed Computer Vision pipelines for industrial defect detection, localization, segmentation, and anomaly heatmap generation using YOLO, Detectron2, SAM3, and DINOv3.
- Implemented text-prompted automatic annotation workflows using SAM 3 to accelerate dataset labeling and improve annotation efficiency.
- Applied OpenCV-based image-processing techniques, including morphological operations and mask refinement, to improve segmentation quality and generate cleaner defect masks.
- Worked with custom datasets covering surface and optical anomalies, including scratches, dents, light bleed, delamination, discoloration, and stains.
- Collaborated with multidisciplinary engineering teams to integrate AI-driven inspection solutions into manufacturing quality-control systems.

### AI Algorithm Engineer
**Shanghai Xiding Intelligent Technology Co., Ltd.** | Shanghai, China  
March 2022 – March 2025

- Developed, trained, and optimized deep learning models for Computer Vision applications, including object detection, student behavior recognition, action recognition, and portrait masking.
- Led the deployment of an on-device inference system on Rockchip RK3588, processing real-time input from three fixed cameras. Managed model conversion, quantization, inference optimization, and accuracy-latency trade-offs for efficient embedded deployment.
- Developed and optimized intelligent scoring models for physics, chemistry, and biology laboratory experiments, migrating AI models and adapting domain-specific expert-system code for Rockchip embedded platforms.
- Contributed to research, data collection, model training, evaluation, and academic publication of a student behavior recognition system.
- Led and contributed to research, prototyping, and evaluation of automated annotation tools integrating the SAM segmentation foundation model.
- Integrated OpenAI API and LangChain-based LLM and RAG pipelines, along with multimodal AI applications using vision-language models (VLMs) for document, image, and video understanding.

### Embedded Engineer
**Youcan Robotics** | Shanghai, China  
November 2021 – February 2022

- Worked on circuit design, simulation, sensor testing, and embedded firmware development across MCU platforms for an underwater robot.

### Faculty, Computer Engineering (Research Assistant)
**Bahria University Karachi** | Pakistan  
April 2021 – October 2021

- Assisted students with coursework and technical projects.
- Supported research initiatives under the supervision of faculty members.

## SELECTED TECHNICAL PROJECTS

### 1. Student Behavior Monitoring in Experimental Exams — Anti-Exam Model and STEAM-Exam Dataset

**Research Publication | AIFE '24, ACM, 2025**

- Developed the Anti-Exam model and contributed to the STEAM-Exam dataset for automated student behavior recognition during junior high school physics, chemistry, and biology practical examinations.
- Integrated MODNet-based portrait matting with YOLOv9 object detection using image inputs from a three-camera AI-assisted scoring device to address occlusion challenges and support suspicious behavior detection.
- Evaluated YOLOv7, YOLOv8, and YOLOv9, with YOLOv9 achieving 98.7% precision, 98.7% recall, 99.4% mAP@50, and 98.6% mAP@50:95.
- Published the research in the proceedings of the 2024 International Conference on Artificial Intelligence and Future Education (AIFE '24).

### 2. Industrial Defect Detection, Segmentation & Anomaly Analysis

- Developed an end-to-end Computer Vision pipeline for industrial defect detection, localization, segmentation, and anomaly visualization, integrating YOLOv11, Detectron2, SAM 2.1, DINOv3, and OpenCV.
- Curated and validated custom datasets covering complex surface and optical defects, including scratches, dents, screen light bleed, discoloration, and delamination.
- Implemented model-assisted annotation workflows using X-AnyLabeling and applied data augmentation.
- Refined segmentation masks through OpenCV-based image-processing techniques and generated anomaly heatmaps and visual inspection outputs for automated quality assessment.

### 3. AI-Powered Image Preprocessing & Defect Segmentation Pipeline

- Designed and implemented an end-to-end Computer Vision preprocessing pipeline for industrial product inspection and reference-based anomaly detection.
- Trained YOLO object detection models to localize target components and integrated SAM 2.1 to extract product regions and remove complex backgrounds.
- Developed OpenCV-based mask refinement techniques, including contour filtering, morphological opening, closing, and dilation, to eliminate unwanted regions and segmentation artifacts.
- Implemented dynamic cropping, padding, and resolution standardization to generate fixed-size (1280 × 800) component images.
- Created a MVTec-style dataset of defect-free reference samples for downstream DINO-based anomaly detection and inspection.

### 4. Automated Visual Annotation Pipeline Using SAM 3

- Developed an automated, model-assisted annotation pipeline using SAM 3 for text-prompted, open-vocabulary object detection and instance segmentation.
- Implemented batch image processing, prompt-based object identification, and automated generation of bounding-box and segmentation-mask annotations in YOLO-compatible formats.
- Generated confidence-scored visualizations for annotation review and validation, streamlining dataset development and reducing manual labeling effort.

### 5. Edge-Deployed Automatic Grading System for Science Laboratory Experiments

- Developed an end-to-end automatic grading system for physics, chemistry, and biology laboratory experiments using custom-trained YOLO models.
- Deployed models on Rockchip RK3588 hardware, integrating real-time inference from three fixed cameras.
- Converted and quantized models into RKNN format and optimized inference performance to balance accuracy and latency.
- Enabled cloud-independent operation and collaborated with hardware and Android engineering teams to validate system performance and support deployment across multiple high schools.

### 6. Multimodal LLM/VLM Application for Document, Image & Video Understanding

- Designed and implemented a multimodal AI application enabling natural-language interaction with documents, images, and videos.
- Integrated models and APIs from OpenAI, Google Gemini, Meta Llama, and Alibaba Qwen using LangChain.
- Built LLM-powered applications with retrieval-augmented generation (RAG) and agentic workflows.
- Implemented document question answering, image scene description and object recognition, and video transcription capabilities.

### 7. On-Device Real-Time Object Detection Android Application

- Developed an offline object detection application using a custom-trained YOLOv5 model.
- Converted the trained model through PyTorch and TensorFlow to TensorFlow Lite (TFLite), applying post-training quantization to reduce model size and improve mobile inference efficiency.
- Integrated the optimized model into a native Android application, implementing live camera input processing, image preprocessing, and real-time bounding-box visualization for on-device inference.

### 8. Embedded AI Board Benchmarking: ROC-RK3588S-PC Performance Evaluation

- Conducted a comparative performance evaluation of Rockchip ROC-RK3588S-PC and RK3399PRO platforms running AI camera software.
- Benchmarked CPU, GPU, NPU, memory utilization, thermal behavior, and video-processing performance using Geekbench 5, 3DMark, AnTuTu, PassMark, and WeTest PerfDog.
- Evaluated high-resolution 4K and 8K video workloads, recording frame rates of 20–61 FPS on the ROC-RK3588S-PC.
- Monitored application performance and resource utilization, observing operating temperatures of approximately 30–32°C on the RK3588S-PC compared with 50–70°C on the RK3399PRO under the tested conditions.
- Demonstrated improved thermal stability and smoother high-resolution video processing on the RK3588S-PC.

## PUBLICATIONS

1. Sun Zhendan, **Zeeshan Hyder**, and Qingfeng Wang. "Student Behavior Monitoring in Experimental Exams: Anti-Exam Model and STEAM-Exam Dataset." In *Proceedings of the 2024 International Conference on Artificial Intelligence and Future Education (AIFE '24)*, pp. 126–134. ACM, 2025. [https://doi.org/10.1145/3708394.3708417](https://doi.org/10.1145/3708394.3708417)

2. **Zeeshan Hyder**, Di He, Dongying Li, and Wenxian Yu. "Improved Wi-Fi Indoor Localization Based on Signal Quality Parameters and RSSI Smoothing Algorithm." In *Proceedings of the 2021 10th International Conference on Information and Automation for Sustainability (ICIAfS)*, pp. 140–144. IEEE, 2021. [https://doi.org/10.1109/ICIAfS52090.2021.9606145](https://doi.org/10.1109/ICIAfS52090.2021.9606145)

## HONORS & AWARDS

- **Best Paper Award (2020)** — IEEE CAS Shanghai and Shikoku Chapters Joint Workshop on Circuits and Systems (SSJW 2020).
- **Chinese Government Scholarship (2018)** — China Scholarship Council, Shanghai Jiao Tong University.
- **Sindh Endowment Scholarship (2014)** — Sukkur IBA University.

## REFERENCES

### Prof. Di He
School of Electronics Information Electrical Engineering (SEIEE)  
Shanghai Jiao Tong University, China  
Email: [dihe@sjtu.edu.cn](mailto:dihe@sjtu.edu.cn)

### Wang Qingfeng
Algorithm Manager (R&D)  
Shanghai Xiding Intelligent Technology Co., Ltd., China  
Email: [eli.wang@xiding.com.cn](mailto:eli.wang@xiding.com.cn)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
