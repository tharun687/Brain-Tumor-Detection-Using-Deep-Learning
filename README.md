# Brain Tumor Detection Using Deep Learning

This repository contains the implementation of advanced deep learning techniques for automated brain tumor detection and segmentation from MRI images. The project explores U-Net architectures and Capsule Networks, leveraging state-of-the-art preprocessing methods to improve diagnostic accuracy.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Dataset](#dataset)
- [Preprocessing Techniques](#preprocessing-techniques)
- [Model Architectures](#model-architectures)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Acknowledgments](#acknowledgments)

## Introduction
Brain tumors are one of the most critical medical challenges, requiring early detection and precise treatment planning. This project addresses the limitations of manual MRI analysis by leveraging deep learning techniques to automate tumor detection and segmentation processes.

## Methodology
The workflow includes:
1. Data preprocessing.
2. Feature extraction.
3. Segmentation using U-Net and Capsule Networks.
4. Evaluation of model performance using appropriate metrics.

## Dataset
The study uses the **BRATS 2019** dataset, which comprises:
- MRI modalities: T1, T2, T1CE, FLAIR.
- Segmentation masks for tumor regions.

## Preprocessing Techniques
- **Log Normalization**: Compresses pixel intensity ranges.
- **Wavelet Transform**: Enhances spatial and frequency features.
- **Gamma Correction**: Adjusts brightness and contrast.
- **Histogram Equalization**: Improves image contrast.

Cumulative histogram equalization was identified as the most effective preprocessing technique.

## Model Architectures
### U-Net
- Encoder-decoder architecture with skip connections.
- Separate models for Low-Grade Glioma (LGG) and High-Grade Glioma (HGG).

### Capsule Networks
- 3D Capsule Network to capture spatial hierarchies and improve segmentation accuracy.

## Evaluation Metrics
- **Intersection Over Union (IoU)**: Measures overlap between predicted and ground truth masks.
- **Dice Similarity Coefficient (DSC)**: Quantifies segmentation accuracy.

## Results
- U-Net achieved high Dice scores and IoU values for LGG and HGG segmentation.
- Capsule Networks demonstrated potential for handling complex spatial relationships.
- Preprocessing techniques significantly improved segmentation performance.

## Conclusion
The project successfully demonstrated the application of deep learning techniques in automating brain tumor detection. The combination of U-Net and Capsule Networks with advanced preprocessing methods showed promising results in improving segmentation accuracy and efficiency.

## Future Work
- Optimization of feature selection using PCA and mRMR.
- Exploration of transformer-based architectures.
- Use of GANs for synthetic data generation.
- Real-world clinical validation.
- Integration of multimodal diagnostic data.
- Longitudinal studies for monitoring tumor progression.

## Acknowledgments
Special thanks to **Dr. Alok Kumar.** for her invaluable guidance and to the **Faculty of Computing And Informatics,Sir Padampat Singhania University,Udaipur,Rajasthan**, for providing resources and support.

---


## Contact
For further inquiries, contact:
- Tharun Puppala: [puppala.tharun@spsu.ac.in](mailto:puppala.tharun@spsu.ac.in)

