# Damaged Apple Detection Using YOLO v9

## Introduction

The "Damaged Apple Detection Using YOLO v9" project aims to utilize advanced machine learning techniques to identify and classify damaged apples in real-time. The YOLO (You Only Look Once) v9 algorithm is known for its speed and accuracy in object detection tasks, making it an ideal choice for this application. This project demonstrates the integration of YOLO v9 with image processing to achieve efficient and accurate detection of damaged apples, which is critical for quality control in agricultural and food industries.

### Objectives

- To develop a robust model capable of accurately detecting damaged apples.
- To implement YOLO v9 for real-time object detection.
- To provide visualizations of the detection process, including output images and performance graphs.

## Methodology

1. **Data Collection**: High-resolution images of apples, including both damaged and undamaged ones, were collected.
2. **Data Annotation**: The images were annotated to mark the regions containing damaged parts.
3. **Model Training**: The annotated dataset was used to train the YOLO v9 model.
4. **Model Evaluation**: The trained model was evaluated on a test set to determine its accuracy and performance.
5. **Real-Time Detection**: The model was deployed to perform real-time detection on new images and video streams.

## Results

### Output Images

Below are some examples of the model's output, showcasing its ability to detect damaged areas on apples:

**VALIDATION PREDICTION**
![val_batch1_pred](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/57cafa2c-44a8-40b3-8851-146838e6c40e)
![val_batch2_pred](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/9da192ed-e72f-404c-ad58-72282d0b3713)

**OUTPUT IMAGES**

![output17](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/a6db5bba-7252-489f-94aa-bcc89b0dcef8), ![output16](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/acb6d6a3-619c-4222-b6f5-4ceb1a30a090), ![output15](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/d3a4490b-bd05-4c81-a5c2-8501baee16ad), 
![output14](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/ec215dcd-e574-4171-b9bc-d9e09dc4f8a9),![output13](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/c99fd489-ed05-4746-8082-06e25ef1eb9d),![output12](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/a07d1c77-ea0e-4cc7-a22d-0a70d77063e7),![output11](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/3ffc2acd-fbef-4c43-8e50-6e26a300baed),![output10](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/81669cc6-b782-4631-ab5f-d6dc4e468594),![output9](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/40c3179c-5c3b-45e4-956a-d279368618ef),![output8](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/8a7927c4-88ef-4217-b17b-32b95f9964c4),![output7](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/530fc2e7-0aba-488a-a967-1790e06afb8d),![output6](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/bc359445-cd20-4de0-bbe6-3a8b3e2ec6d8),![output5](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/bb10f283-7b9b-4948-874c-789354b3cb21),![output4](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/b7c94d7d-8a82-4aff-a456-7f940a6726c1),![output3](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/ef342f3e-2b34-44b1-a4b0-78cbdef030bc),![output2](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/e884dbf3-e7fb-4b71-b549-6d9518e87040),![output1](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/16a3c055-df77-40c9-b6c8-e71f15b313df),![output18](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/bd5cc63a-9005-4411-b12e-f9809c4ebbcb)

### Performance Graphs

The following graphs illustrate the performance metrics of the model:

**RESULTS**
![results (1)](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/0812b63c-001b-489c-80b3-bffa747dbd68)

**CORRELOGRAM**
![labels_correlogram](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/e16798f1-3ee2-4274-9cea-8cd4d7b713cd)

**LABELS**
![labels](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/162b62ff-a0e1-47c8-a3b5-0133889bce58)

**CONFUSION MATRIX**
![confusion_matrix](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/1c41f3de-df84-4d8f-bd62-4f16bf949f78)

**R_CURVE**
![R_curve](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/1b3e5088-6a31-4db1-9e68-88edd5487d7f)

**P_CURVE**
![P_curve](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/6b7bedba-87f4-434b-b94e-b86244f45b24)

**PR_CURVE**
![PR_curve](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/1a0172e6-82b3-4837-9061-feb3a77a0c63)

**F1 CURVE**
![F1_curve](https://github.com/DeepikaA2004/Damaged-Apple-Detection-using-YOLO-V9/assets/110418508/e84458ef-9d75-4767-b923-bbb0dbf00bb1)

## Conclusion

The "Damaged Apple Detection Using YOLO v9" project successfully demonstrates the application of state-of-the-art object detection techniques to address a real-world problem in the agricultural sector. By leveraging the powerful YOLO v9 algorithm, the project achieved high accuracy in identifying and classifying damaged apples, facilitating efficient and effective quality control processes.

The model's performance, as evidenced by the provided output images and performance graphs, showcases its potential for deployment in various settings, including farms, packaging facilities, and retail environments. Integrating this technology can significantly improve product quality, waste reduction, and overall operational efficiency.

Future work may focus on further optimizing the model, expanding the dataset to include a wider variety of apple types and damage conditions, and exploring the use of this approach for other fruits and vegetables. Additionally, real-time deployment on edge devices could be explored to enhance portability and usability in field conditions.

Overall, this project underscores the value of combining machine learning with practical applications, paving the way for innovative solutions in the agricultural industry.

## Contact

**MY LINKEDIN PROFILE** - https://www.linkedin.com/in/deepika2004/

