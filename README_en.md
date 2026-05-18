# Wild Chrysanthemum Dataset

## Overview

This dataset contains photos and videos of wild chrysanthemum fields, as well as image frames extracted from them that include bee behavior. All data are raw and unannotated, suitable for computer vision, image recognition, bee behavior research, and other fields.

## Directory Structure

```
WildChrysanthemum/
├── raw/                    # Original photos
│   ├── *.jpeg             # Wild chrysanthemum photos taken by camera (287 files)
│   └── *.jpg              # Frames extracted from videos (4 files)
├── raw_media/             # Original videos
│   ├── *.MOV              # HDR video files (4 files)
│   ├── *.mp4              # HDR video files (3 files)
│   └── README.md          # Video documentation
└── Select/                # Selected video frames
    ├── BeesInField/       # Sequential frames of bees in wild chrysanthemum field
    ├── BeesOnField2/      # Sequential frames of bees in wild chrysanthemum field (Part 2)
    └── README.txt         # Image documentation
```

## Data Specifications

### Photos (raw/)

- **Format**: JPEG (.jpeg) and JPG (.jpg)
- **Resolution**: 4000×3000 pixels or higher
- **DPI**: Both horizontal and vertical resolutions ≥ 72 DPI
- **Bit Depth**: 24-bit
- **Focal Length**: Approximately 23mm and 70mm equivalent full-frame
- **Content**:
  - .jpeg files: Wild chrysanthemum photos taken directly by camera
  - .jpg files: Frames extracted from videos

### Videos (raw_media/)

- **Format**: MOV and MP4
- **Feature**: HDR format
- **Focal Length**: Approximately 23mm and 70mm equivalent full-frame
- **Content**: Videos containing bees flying through or visiting flowers in wild chrysanthemum fields

### Selected Images (Select/)

- **Content**: Selected frames extracted from videos
- **Features**: Each frame contains bees flying and visiting flowers in wild chrysanthemum fields, all are sequential frames
- **Status**: Raw data, unannotated and unmodified

## Usage

This dataset can be used for:
- Bee behavior recognition research
- Flower recognition and classification
- Computer vision model training
- Wild chrysanthemum field ecological observation
- Image segmentation and object detection

## Notes

- All data are originally collected, without manual annotation
- Video files use HDR format with higher dynamic range
- Image resolution is high, suitable for detailed image analysis tasks

## Contact

- Email: [3224183364@qq.com]
- Author: [Aolin Zhou]
