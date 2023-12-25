<h1 align=center><font size = 6>Deep Learning-Based Scene Classification Of VHR Satellite Imagery For Post-Earthquake Damage Assessment</font></h1>

<img  src="https://raw.githubusercontent.com/geoaihub/geoaihub/main/assets/Mersin%20GeoAI%20Hub%202.png"  height=400  width=1000  alt="https://github.com/geoaihub"/>  

<small>Picture Source: <a  href="https://github.com/geoaihub">GeoAI Hub Mersin</a></small>

<br>

## Overview

This repository features a deep learning-based system for classifying scenes in very high-resolution (VHR) satellite imagery, with a focus on post-earthquake damage assessment. The primary case study involves the devastating earthquakes that occurred in Kahramanmaraş province, Türkiye, in 2023.

<br>

## Abstract

Following the devastating earthquakes in Kahramanmaraş province, Türkiye, on February 6, 2023, which resulted in the loss of over 50,000 lives and damage to more than 84,000 buildings, the pressing need for efficient damage assessment and response became apparent. Traditional on-site assessments are time-consuming and perilous. Most existing research leans towards segmentation and object detection methods for earthquake damage assessment using remotely sensed data, which demand substantial training data, computational resources, and time. A more practical approach can be classifying image patches to identify earthquake-affected areas with damaged buildings. This scene classification method categorizes image patches based on their content. Remote sensing scene classification assigns labels to such images using deep learning various algorithms.

<br>

In this work, we developed a fully automated system utilizing Maxar’s very high-resolution post-earthquake satellite imagery to classify and map the scenes (image patches) involving collapsed and non-collapsed buildings in Antakya and Iskenderun city centers. Our approach involved two key scene classifiers: Classifier #1, employing deep learning models like ResNet-101, effectively detected building presence within the image scene with remarkable accuracy (99.17%). This classifier served as the foundation for identifying the scenes involving buildings for entire city in order to filter the non-urban land use. Then, Classifier #2, classified building scenes into collapsed and non-collapsed categories. The DenseNet-121 model excelled, achieving an accuracy of 93.33% in this task. In the end, Classifier #2 categorized 2,429 non-collapsed and 449 collapsed scenes in Antakya and 2,291 non-collapsed and 290 collapsed scenes in Iskenderun.

<br>

## Key Features

- Utilizes Maxar's very high-resolution post-earthquake satellite imagery.
- Two-stage scene classification:
  - **Classifier #1:** Detects building presence.
  - **Classifier #2:** Categorizes scenes into collapsed and non-collapsed buildings.
- Deep learning models, including ResNet-101 and DenseNet-121, are employed for accurate and efficient classification.
- Results from Antakya and Iskenderun city centers with detailed accuracy metrics.

<br>

## Installation

    bash
    # Clone the repository
    git clone https://github.com/geoaihub/GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras.git
    
    # Change directory
    cd GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras

<br>

## Why Use This Repository

- Efficient and automated earthquake damage assessment using satellite imagery.
- Practical approach with scene classification, reducing the need for extensive training data and computational resources.
- Valuable insights for humanitarian aid efforts and post-earthquake response planning.

<br>

## Citation

    @article{...,
      author = {...},
      doi = {...},
      month = {...},
      title = {...},
      url = {...},
      version = {...},
      year = {...}
    }
