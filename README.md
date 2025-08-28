# Cognitive-impairment-detection-in-healthy-patients-

## Overview
This project selects the top 300 MRI images for healthy and unhealthy patients and extracts intensity, texture, and morphological features. These features are then used for feature extraction which later on undergo machine learning classifiers for prediction modelling. 

## Folder Structure
- Code/: MATLAB scripts
- Results/: Excel feature files
- Data/: Sample MRI images (optional)

## How to Run
1. Update `main_folder` paths in MATLAB scripts to point to your MRI images.
2. Run selection scripts first:
   - `select_best_healthy.m`
   - `select_best_unhealthy.m`
3. Then run feature extraction scripts:
   - `extract_features_healthy.m`
   - `extract_features_unhealthy.m`
4. Features are saved in the `Results/` folder.

## Dependencies
- MATLAB R2022a or newer
- Image Processing Toolbox
