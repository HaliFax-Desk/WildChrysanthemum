# WildFloralCluster\-MultiView Dataset README

\# WildFloralCluster\-MultiView Dataset

\#\# Dataset Introduction

This dataset is a multi\-view high\-definition image collection of wild herbaceous flower clusters in outdoor natural scenes\. Collected under real natural lighting conditions and variable environmental backgrounds, it adopts a surround multi\-angle fixed\-point shooting method, covering different orientations, distances and depth of field changes\. It fully retains the original high\-definition imaging details and native characteristics of vegetation without excessive artificial modification or scene intervention\.

The dataset includes raw unprocessed images and sorted, calibrated finished images, which can be directly used for the training and verification of related algorithms such as image classification, object detection, multi\-view feature matching, scene reconstruction, and vegetation visual perception\. It provides real and reliable open\-source data support for machine vision research in natural wild scenes\.

\#\# Dataset Details

\#\#\# 1\. Collection Parameters

- **Shooting Environment**: Outdoor natural suburban scenes, covering common natural lighting conditions such as sunny days and cloudy days, without extreme weather interference\.

- **Shooting Equipment and Image Specifications**:


    - Image Resolution: \`4032 × 3024\` pixels \(basic high definition\), bit depth 24 bits, horizontal/vertical resolution both 72 dpi, retaining complete color details and texture information\.

    - Image Format: Standard compression format, no additional artificial modification, natively restoring scene features\.

- **Camera Native Settings**:
        

    - Aperture Value: \`f/2\.8\`

    - Exposure Time: \`1/99 s\`

    - ISO Sensitivity: \`ISO\-50\`

    - Exposure Compensation: \`0 EV\`

    - Focal Length: \`9 mm\`

    - Metering Mode: Pattern Metering

- **Shooting Angles**: Surrounding the main body of the flower cluster, multi\-directional fixed\-point shooting is set, covering multiple angles such as front, side, top\-down and bottom\-up, with a distance range of 0\.5–2\.0 meters, fully presenting the three\-dimensional shape and details of the flower cluster\.

- **Number of Images**: A total of 289 high\-definition raw images; 4K resolution images will be supplemented and updated later\.

\#\#\# 2\. Directory Structure

```plain text
WildFloralCluster-MultiView/
├── README.md           # Dataset description document (this document)
├── raw/                # Raw unprocessed high-definition images (directly output by the camera, no any modification)
├── processed/          # Processed images (uniform composition, size calibration, can be directly used for experiments)
│   ├── train/          # Training set (adjustable according to actual division)
│   ├── val/            # Validation set (adjustable according to actual division)
│   └── test/           # Test set (adjustable according to actual division)
├── annotations/        # Annotation files (if any, such as XML/JSON format, delete this directory if not available)
└── scripts/            # Data processing scripts (data cleaning, format conversion, enhancement scripts, delete this directory if not available)
```

\#\#\# 3\. Data Processing Description

- Raw Data \(raw/\): Directly output by the camera, retaining the original shooting parameters, light and shadow details and environmental background, without any cropping, filtering or color adjustment\.

- Processed Data \(processed/\): Minor sorting is performed on the raw images, including uniform image size, correction of shooting angle deviation, and removal of a small number of blurred/abnormal images\. The core features of the images and the original appearance of the vegetation are not changed, which can be directly used for model training and experimental reproduction\.

- Annotation Files \(annotations/\): If annotations are included, the annotation content includes the bounding box of the flower cluster area, vegetation category, etc\. \(modify according to actual annotation content\), and the format is uniformly XML/JSON for easy model call\.

\#\# Usage Instructions

- This dataset is only for academic research, education and non\-commercial purposes\. Commercial development, infringement and dissemination are prohibited\.

- When using this dataset for research or publishing papers, please cite this dataset \(see the citation format below\)\.

- After downloading the dataset, the images in the processed/ directory can be directly extracted for experiments, and the images in the raw/ directory can be used for data enhancement, comparative experiments and other purposes\.

- If you need to use the scripts/ directory for data processing, please ensure that the environment dependencies \(such as Python, OpenCV, etc\.\) are configured correctly, and refer to the comments in the scripts for specific operations\.

\#\# Citation Format

If you use this dataset in your published paper, please cite it in the following format:

```plain text
@dataset{WildFloralCluster-MultiView,
  author = {Your Name/Team Name},
  title = {WildFloralCluster-MultiView: A Multi-View High-Definition Image Dataset of Wild Herbaceous Flower Clusters},
  year = {2026},
  publisher = {GitHub},
  url = {Your GitHub Repository Link},
  doi = {Your Zenodo DOI (if available)}
}
```

\#\# Contact Information

If you have any questions, suggestions or usage issues related to the dataset, please contact us through the following methods:

Email: [3224183364@qq\.com](mailto:3224183364@qq.com)

GitHub: [https://github\.com/HaliFax\-Desk](https://github.com/HaliFax-Desk)

> （注：文档部分内容可能由 AI 生成）
