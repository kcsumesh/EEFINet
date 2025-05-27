# EEFINet
This repository contains the official PyTorch code base for **Multi-task architecture with edge enhancement and feature interaction for smallholder agricultural field delineation**.

```
Our code will be released soon after the paper is accepted.
```

## Introduction

## Using the code
The code is stable while using *Python 3.10.4*, *PyTorch 2.1.2* and *CUDA version 12.4*.
```
The further instructions on using the code will be released soon after the paper is accepted.
```

## Data
AI4SmallFarms is an open, large-scale smallholder agricultural field boundayr data consisting of 439,001 field polygons and Sentinel-2 image (10 m) distributed across Vietnam and Cambodia. It also provides a freely available agricultural field boundary dataset and Sentinel-2 images from the Netherlands. The dataset can be obtained from https://easy.dans.knaw.nl/ui/datasets/id/easy-dataset:321745.

We have extended the AI4SmallFarms dataset by including a high-resolution PlanetScope images (3 m), which could aid in improving the delineation of smallholder fields in Vietname and Cambodia. *The link to dataset will be shared after the paper is accepted.*

## Preprocessing

## Folder and data structure
The folder and data structure should be as follows:
```
inputs
└── train
    └── images
        ├── 001.tif
        ├── 002.tif
        ├── 003.tif
        ├── ...
    └── masks
        ├── 001.tif
        ├── 002.tif
        ├── 003.tif
        ├── ...
    └── contours
        ├── 001.tif
        ├── 002.tif
        ├── 003.tif
        ├── ...
└── validate
    └── images
        ├── 001.tif
        ├── 002.tif
        ├── 003.tif
        ├── ...
    └── masks
        ├── 001.tif
        ├── 002.tif
        ├── 003.tif
        ├── ...
    └── contours
        ├── 001.tif
        ├── 002.tif
        ├── 003.tif
        ├── ...
└── test
    └── images
        ├── 001.tif
        ├── 002.tif
        ├── 003.tif
        ├── ...
    └── masks
        ├── 001.tif
        ├── 002.tif
        ├── 003.tif
        ├── ...
    └── contours
        ├── 001.tif
        ├── 002.tif
        ├── 003.tif
        ├── ...
```

## Training and testing

## Citation


## Acknowledgement
**Data Source**
```
@article{ai4small,
  title={AI4SmallholderFarms: A Large-scale Data Set for Crop Field Delineation in Smallholder Farms in Southeast Asia},
  author={Persello, Claudio and Grift, Jeroen and Xinyan, Fan and Paris, Claudia and Hänsch, Ronny and Koeva, Mila and Nelson, Andy},
  journal={{IEEE GEOSCIENCE AND REMOTE SENSING LETTERS},
  volume={20}
  number={}
  pages={1-5}
  year={2023}
}
```
