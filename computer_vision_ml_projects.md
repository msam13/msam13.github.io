---
layout: default
title: Computer Vision Projects
---

# Computer Vision Projects

## Custom CPU for ML Experiments

**Overview:** Built a custom CPU from scratch specifically for running machine learning experiments.

**Components Used:**

- **Motherboard**: [ASRock X670E TAICHI CARRARA](https://www.amazon.com/ASRock-X670E-Carrara-Processors-Motherboard/dp/B0BGPGH6WG)
- **CPU**: [AMD Ryzen 9 7000 series 16 core 32 thread](https://www.amazon.com/AMD-Ryzen-7950X3D-Hexadeca-core-Processor/dp/B0BTRH9MNS/ref=asc_df_B0BTRH9MNS/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=16695656210843621867&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032188&hvtargid=pla-2281435182178&psc=1&mcid=5e8c836c59dd345693791cc7774e27b0&hvocijid=16695656210843621867-B0BTRH9MNS-&hvexpln=73&gad_source=1)
- **GPU**: [Nvidia GEFORCE RTX 4090 24GB](https://www.amazon.com/PNY-GeForce-RTXTM-4090-Triple-Graphics/dp/B0BHBTJ2X2/ref=asc_df_B0BHBTJ2X2/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=513373364324449578&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032188&hvtargid=pla-2281435180498&psc=1&mcid=a87160cbd7673419ab1d1acbda190734&hvocijid=513373364324449578-B0BHBTJ2X2-&hvexpln=73&gad_source=1)
- **RAM**: [VENGEANCE LPX DDR5 64GB (2x32GB)](https://www.amazon.com/Corsair-VENGEANCE-3200MHz-Compatible-Computer/dp/B07Y4ZZ7LQ/ref=asc_df_B07Y4ZZ7LQ/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=2481200149637809416&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032188&hvtargid=pla-2281435181178&mcid=236136ef8073388db43eb666b9e7b713&hvocijid=2481200149637809416-B07Y4ZZ7LQ-&hvexpln=73&gad_source=1&th=1)
- **Hard Drive**: [WD - BLACK SN850X 2TB](https://www.amazon.com/WD_BLACK-SN850X-Internal-Gaming-Solid/dp/B0B7CMZ3QH)
- **Power Supply**: [Gamemax 1300w](https://www.amazon.com/GAMEMAX-Addressable-Motherboard-105%C2%B0C-Rated-Capacitors/dp/B0BCKHHVYW/ref=asc_df_B0BCKHHVYW/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=3473661350933650431&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032188&hvtargid=pla-2281435180058&psc=1&mcid=4916f6ee34c33a3bb00e04a893bb1e9a&hvocijid=3473661350933650431-B0BCKHHVYW-&hvexpln=73&gad_source=1)
- **Cooling System**: [Hyper 212 Halo](https://www.amazon.com/Cooler-Master-Aluminum-LGA1700-RR-S4KK-20PA-R1/dp/B0BRBWL38D/ref=asc_df_B0BRBWL38D/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=1568772745099818266&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032188&hvtargid=pla-2281435178818&psc=1&mcid=d4fab3989c66355d8e89b9f1eea5a3a7&hvocijid=1568772745099818266-B0BRBWL38D-&hvexpln=73&gad_source=1)

<div style="display: flex; flex-wrap: wrap;">
  <div style="flex: 1; padding: 10px;">
    <img src="images/CVimages/build1.jpg" alt="Product 1" style="max-width: 100%; height: auto;">
  </div>
  <div style="flex: 1; padding: 10px;">
    <img src="images/CVimages/build2.jpg" alt="Product 3" style="max-width: 100%; height: auto;">
  </div>
</div>
<div style="display: flex; flex-wrap: wrap;">
  <div style="flex: 1; padding: 10px;">
    <img src="images/CVimages/build3.jpg" alt="Product 1" style="max-width: 100%; height: auto;">
  </div>
  <div style="flex: 1; padding: 10px;">
    <img src="images/CVimages/build4.jpg" alt="Product 3" style="max-width: 100%; height: auto;">
  </div>
</div>

## 3D-Ready

**Overview:** The 3D-Ready application leverages a modern stack including React for the frontend and FastAPI for the backend, seamlessly integrated with various AWS services like Amplify, Lambda, S3, DynamoDB, and API Gateway.

**Deployment:** Utilizing AWS's robust infrastructure, the application ensures high availability and scalability, offering users an efficient and reliable experience for generating and viewing 3D models.

**Media Files and Links:**

<div style="flex: 1; padding: 10px;">
  <img src="images/architecture.png" alt="Product 3" style="max-width: 100%; height: auto;">
</div>

- [Link full detailed architecture](3d-ready.md)
- [Link to 3D ready](https://3-dready.com/)

## Experiment : NeRO Bell

**Overview:** This project involves experimenting with NeRO (Neural Geometry and BRDF Reconstruction of Reflective Objects from Multiview Images) to create a high-quality 3D model of a bell. The goal is to leverage NeRO's advanced neural geometry and BRDF (Bidirectional Reflectance Distribution Function) reconstruction techniques to achieve precise and realistic 3D representations of reflective objects.

**Technical Approach:** -

- NeRO: For neural geometry and BRDF reconstruction from multiview images.
- Python: For scripting, data processing, and automation of the pipeline.
- PyTorch: As the deep learning framework to implement and train the NeRO model.
- CUDA: For GPU acceleration to enhance processing efficiency and speed.
- Blender : For Rendering

<iframe width="560" height="315" src="https://www.youtube.com/embed/6TdkTVGHfC8?si=N-i4y1BwlmY7pbmo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Experiment : NeRF Fox

**Overview:** This project creating a Neural Radiance Field (NeRF) of a fox using instant NGP. The result is a high-fidelity 3D representation of the fox that can be rendered from various viewpoints.

**Technical Approach:** -

- instant NGP: For generating the NeRF.
- Python: For scripting and automation.
- CUDA: For GPU acceleration.

**Media Files and Links:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/nDbLZIRgzNE?si=YA8Fk6nYM_gUgNSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## 2D Image Fitting Using KAN (Kolmogorov–Arnold Networks)

**Overview:** This project involves fitting 2D images (MNIST) using Kolmogorov–Arnold Networks (KAN) to improve image representation and reconstruction.

**Technical Approach:** The project utilizes Kolmogorov–Arnold Networks for effective 2D image fitting, leveraging advanced mathematical techniques to achieve high accuracy in image reconstruction.

**Media Files and Links:**

- [Link to 2D Image Fitting Using KAN Repository](https://github.com/msam13/Kan-ImageFitting)

## Structure from Motion

**Overview:** This project focuses on the structure from motion (SfM) technique using Python, Numpy, OpenCV, and GPU to reconstruct 3D structures from 2D images.

**Technical Approach:** The SfM technique is implemented using Python and libraries like Numpy and OpenCV. GPU acceleration is utilized to enhance computational efficiency.

**Media Files and Links:**

- COLAMP SMF
<iframe width="560" height="315" src="https://www.youtube.com/embed/AKy6pkxb6Zc?si=RB3QLBeCKmMY_qtY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- COLMAP POINTCLOUD
<iframe width="560" height="315" src="https://www.youtube.com/embed/5iAL4NZKW_0?si=LskwNymogwJCvmCb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Image Classifier Using PyTorch

**Overview:** Rebuilt the OG PyTorch-based image classification project to accurately categorize images into predefined classes, demonstrating proficiency in deep learning and computer vision.

**Technical Approach:** Implemented a Convolutional Neural Network (CNN) with multiple convolutional and fully connected layers, utilizing ReLU activation, max pooling, and backpropagation for training, while leveraging the Stochastic Gradient Descent (SGD) optimizer and cross-entropy loss for efficient learning. Model trained on CIFAR10 datatset.

**Media Files and Links:**

- [Link to Digit Classifier Using PyTorch Repository](https://github.com/msam13/CNNImageClassifier)

  <div style="flex: 1; padding: 10px;">
    <img src="images/imageclassifier.png" alt="Product 3" style="max-width: 100%; height: auto;">
  </div>
