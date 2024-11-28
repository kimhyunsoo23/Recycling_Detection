# Recyclable Glass Bottle Detection AI
### **재활용 유리병 탐지 AI**

---

## **Overview / 개요**

**English:**  
This project focuses on developing an AI system capable of detecting recyclable glass bottles using computer vision and machine learning techniques. The detection system is built on the **YOLOv5 (You Only Look Once)** object detection framework, which is known for its real-time speed and high accuracy. By automating the detection of recyclable glass bottles, the system enhances waste management and recycling processes, ensuring greater efficiency and sustainability.

**한국어:**  
이 프로젝트는 **컴퓨터 비전**과 **머신러닝** 기술을 활용하여 재활용 가능한 유리병을 탐지하는 AI 시스템을 개발하는 것을 목표로 합니다. 본 시스템은 **YOLOv5 (You Only Look Once)** 객체 탐지 모델을 기반으로 하며, 빠른 속도와 높은 정확도를 제공합니다. 재활용 유리병 탐지를 자동화함으로써 폐기물 관리와 재활용 효율성을 극대화하고, 지속 가능성을 높이는 데 기여합니다.

---

## **Purpose / 목적**

- **Automated Sorting / 자동 분류**  
  Efficiently identify and separate recyclable glass bottles from waste streams to improve recycling rates.  
  폐기물 처리 과정에서 재활용 가능한 유리병을 효율적으로 식별하고 분류하여 재활용률을 향상합니다.

- **Waste Management / 폐기물 관리**  
  Assist waste management facilities in streamlining the recycling process by automating bottle detection.  
  유리병 감지 자동화를 통해 폐기물 관리 시설의 작업을 간소화하고 효율성을 높입니다.

- **Environmental Sustainability / 환경 지속 가능성**  
  Contribute to environmental protection by ensuring that recyclable glass bottles are properly processed.  
  재활용 가능한 유리병이 올바르게 처리되도록 하여 환경 보호에 기여합니다.

---

## **How It Works / 작동 원리**

### **1. Dataset / 데이터셋**
- **Images**: The dataset includes images of recyclable glass bottles in various forms (whole, partially damaged, and dirty).  
  데이터셋에는 다양한 상태(온전한 병, 일부 손상된 병, 오염된 병)의 재활용 유리병 이미지가 포함됩니다.
- **Annotations**: Each image is labeled with bounding boxes to distinguish glass bottles from other objects.  
  각 이미지는 바운딩 박스로 라벨링되어 유리병과 다른 객체를 구분합니다.

### **2. Model Architecture / 모델 구조**
- YOLOv5 is used to detect glass bottles with high precision and speed, ensuring reliable performance in real-time applications.  
  YOLOv5는 높은 정밀도와 속도로 유리병을 탐지하여 실시간 응용 환경에서도 신뢰할 수 있는 성능을 제공합니다.

### **3. Training / 학습**
- **Data Augmentation**: Techniques such as rotation, brightness adjustment, and flipping are applied to improve robustness.  
  회전, 밝기 조정, 반전 등의 데이터 증강 기술을 사용하여 모델의 강건성을 강화합니다.
- **Optimization**: The model is trained over multiple epochs to maximize precision and recall.  
  다수의 에포크 동안 학습하여 정밀도와 재현율을 극대화합니다.

### **4. Deployment / 배포**
- The system processes live video feeds or static images to detect recyclable glass bottles and highlight them with bounding boxes.  
  실시간 비디오 스트림 또는 정적 이미지를 분석하여 재활용 유리병을 탐지하고 바운딩 박스로 표시합니다.
- The model can be deployed on edge devices such as Jetson Nano or integrated into recycling facility workflows.  
  Jetson Nano와 같은 엣지 장치에 배포하거나 재활용 시설 작업 흐름에 통합할 수 있습니다.

---

## **Features / 특징**

- **High Accuracy / 높은 정확도**  
  Effectively detects recyclable glass bottles, even in cluttered environments.  
  복잡한 환경에서도 재활용 유리병을 효과적으로 탐지합니다.

- **Real-Time Processing / 실시간 처리**  
  Processes video streams or images instantly, enabling fast and accurate sorting.  
  비디오 스트림이나 이미지를 실시간으로 처리하여 신속하고 정확한 분류를 가능하게 합니다.

- **Customizable Alerts / 맞춤형 알림**  
  Sends notifications for specific conditions, such as detecting contaminated or non-recyclable bottles.  
  오염되었거나 재활용이 불가능한 병을 감지할 경우 맞춤형 알림을 제공합니다.

---

## **Future Enhancements / 향후 개선점**

- **Dataset Expansion / 데이터셋 확장**  
  Include additional variations of glass bottles, such as colored or specialty glass, to improve model robustness.  
  유리병의 색상, 특수 재질 등을 포함하여 데이터셋을 확장함으로써 모델의 강건성을 높입니다.

- **Edge Optimization / 엣지 최적화**  
  Enhance the model’s performance for deployment on low-power devices like Raspberry Pi or Jetson Nano.  
  Raspberry Pi 또는 Jetson Nano와 같은 저전력 장치에서도 효율적으로 작동하도록 모델을 최적화합니다.

- **Multi-Material Detection / 다중 재료 탐지**  
  Extend the system’s capabilities to detect other recyclable materials such as plastic bottles, aluminum cans, and paper.  
  플라스틱 병, 알루미늄 캔, 종이 등 다른 재활용 가능한 재료도 탐지할 수 있도록 시스템의 기능을 확장합니다.

---

## **Conclusion / 결론**

This Recyclable Glass Bottle Detection AI project provides an innovative solution for waste management and recycling. By automating the detection and sorting of glass bottles, the system not only improves operational efficiency but also contributes to a more sustainable and environmentally-friendly future. Its scalability and adaptability make it a valuable tool for recycling facilities and waste management industries.  
본 재활용 유리병 탐지 AI 프로젝트는 폐기물 관리와 재활용 작업을 위한 혁신적인 솔루션을 제공합니다. 유리병 감지와 분류를 자동화함으로써 작업 효율성을 향상시키고, 지속 가능하고 친환경적인 미래에 기여할 수 있습니다.

---
