# BLUE-Net-BLUmberg-function-based-Ensemble-Network-for-Liver-and-Tumor-Segmentation-from-CT-scans

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SuryaMajumder/BLUE-Net-BLUmberg-function-based-Ensemble-Network-for-Liver-and-Tumor-Segmentation-from-CT-scans/blob/main/Ensemble-Liver.ipynb) and [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SuryaMajumder/BLUE-Net-BLUmberg-function-based-Ensemble-Network-for-Liver-and-Tumor-Segmentation-from-CT-scans/blob/main/Ensemble-Tumor.ipynb)

#### [Surya Majumder](https://www.linkedin.com/in/surya-majumder-333891246/)\*, [Arup Sau](https://www.linkedin.com/in/arup-sau-6503a4184/)\*, [Akash Halder](https://in.linkedin.com/in/akash-halder-1b315b1b7)\*, [Priyam Saha](https://in.linkedin.com/in/priyam-saha-69308a226)\*, and [Ram Sarkar](http://www.jaduniv.edu.in/profile.php?uid=686)\*
\* Equally contributing first authors


This is the official implementation of "BLUE-Net: BLUmberg Function-Based Ensemble Network for Liver and Tumor Segmentation from CT
Scans".

### Overall workflow:
![model architecture](https://github.com/user-attachments/assets/9b3ce863-035f-4175-b801-c7607096d4a0)


## Abstract
Liver segmentation plays a significant role in medical image analysis based diagnosis for liver-related diseases like liver cancer. Recently, deep learning models, particularly U-Net-like architectures, have obtained notable success in medical image segmentation. Ensemble learning is a powerful approach that helps leverage the performance of an overall model by incorporating the decisions of multiple models. In this paper, we propose an ensemble learning model, called BLUE-Net (BLUmberg function based Ensemble Network), for liver as well as tumor segmentation from computed tomography (CT) scan images using a combination of three models, namely the basic U-Net, Link-Net, and Feature Pyramid Network(FPN). We combine the decisions of these models with a fuzzy-ranking scheme by using a modified Blumberg function to decide whether a pixel in a CT scan image is a part of a foreground pixel of the segmentation mask. We have evaluated our model on the publicly available 3DIRCADb liver and liver tumor segmentation dataset, and the obtained results demonstrate the usefulness of ensemble learning in improving segmentation performance in comparison to state-of-the-art methods.


## Results

| Visualizations                     | U-Net                              | Link-Net                           | FPN                                |
|------------------------------------|------------------------------------|------------------------------------|------------------------------------|
| Heatmaps | ![unet-heatmap](https://github.com/user-attachments/assets/d6a95d10-9b91-4da4-8119-32a4cf924fcb) | ![linknet-heatmap](https://github.com/user-attachments/assets/3e0d572f-e697-4dc1-9823-c69b021781e1) | ![fpn-heatmap](https://github.com/user-attachments/assets/88aa224c-37f4-4ed4-b40f-8184a0756606) |
| GradCams | ![Unet-GradCam](https://github.com/user-attachments/assets/b6e763be-0c0f-47da-8466-882935cbdd5a) | ![LinkNet-GradCam](https://github.com/user-attachments/assets/80fcde7e-69b7-498d-ab47-d295fb0920bc) | ![FPN-GradCam](https://github.com/user-attachments/assets/4f401890-9b2a-42e9-845f-36d4afa63022) |
| Activation Maps | ![unet activation](https://github.com/user-attachments/assets/1c16feee-4fc0-4ac5-9b88-69bd128dbfdc) | ![linknet activation](https://github.com/user-attachments/assets/dba3b8e9-99d8-4473-993e-2deee8871de9) | ![fpn activation](https://github.com/user-attachments/assets/765d589e-bd89-4005-8622-a0bdd837768c) |
| IOU Maps | ![unet iou](https://github.com/user-attachments/assets/2a5b260f-bdd8-43ef-a568-3f2af56f8505) | ![linknet iou](https://github.com/user-attachments/assets/9374e9b0-26da-4a65-85b7-072d8c0b2934) | ![fpn iou](https://github.com/user-attachments/assets/6fbb7146-6969-4c41-96e0-6e03f532db61) |

## Citation:
Please do cite our paper in case you find it useful for your research.<br/>
Citation-<br/>

<br/>
-Link to our paper-<br/>
