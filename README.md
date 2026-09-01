# ECG Digitalization Analysis

## Overview

This project contains an exploratory analysis of an ECG image digitization dataset. The notebook studies both the original ECG time-series signals and their corresponding image representations.

The analysis focuses on understanding the dataset before building a digitization or reconstruction pipeline.

## What is covered

- Dataset and metadata inspection
- Sampling-frequency distribution
- Signal length and recording duration
- 12-lead ECG structure
- Comparison between stored signal duration and displayed image duration
- ECG image dimensions and pixel properties
- Original and grayscale image inspection
- Comparison of different image-quality variants
- Local degradation analysis
- ECG grid and line detection
- Image projection analysis
- Signal statistics for each lead
- Correlation between ECG leads
- Time-domain and frequency-domain analysis
- Test-data structure and prediction requirements

## Dataset

The notebook is configured for the dataset path:

`/kaggle/input/physionet-ecg-image-digitization`

If you run the notebook outside Kaggle, update the `DATA_PATH` variable accordingly.

## Requirements

The notebook uses:

- numpy
- pandas
- matplotlib
- seaborn
- opencv-python
- Pillow
- scipy
- plotly

## Run

Open `ECG_Digitalization_Analysis.ipynb` in Kaggle or Jupyter and run the cells in order.
