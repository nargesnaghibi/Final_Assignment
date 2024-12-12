# Visualization of Stereotactic Synthesis of Functional Abnormalities in Dyslexia

## Developer
Narges Naghibi

## Publication Date
December 4, 2024

## Data Source
[Neurosynth Dyslexia Analysis](https://neurosynth.org/analyses/terms/dyslexia/)

## Overview
This project is part of the course "Programming for Psychologists". It involves the visualization of functional abnormalities in dyslexia using data obtained from the Neurosynth platform. The data includes the stereotactic results of an automated meta-analysis of all studies in the Neurosynth database whose abstracts include the term "dyslexia" at least once.

## Sections

### 1. Importing NIFTI Images
In this section, we load the statistical map and anatomical image using the `nilearn` library. An interactive plot is created to visualize the data.

### 2. Visualizing the Statistical Map with Anatomical Image
We visualize the statistical map overlaid on the anatomical image using the `plot_stat_map` function from the `nilearn` library.

### 3. Finding and Visualizing the Peak Activation Voxel
This section identifies the voxel with the maximum statistical value in the statistical map and visualizes it with a crosshair indicating the peak activation voxel.

### 4. Visualizing the Histogram of Positive Values in the Statistical Map
We visualize the distribution of positive values in the statistical map using a histogram.

### 5. Comparing Hemispheric Differences in the Functional Abnormalities of Dyslexia
This section explores the lateralization of functional abnormalities by comparing the distribution of positive values in the left and right hemispheres of the brain.

## Requirements
- Python 3.x
- nilearn
- numpy
- nibabel
- matplotlib

## Usage
1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook to reproduce the visualizations.

## License
This project is licensed under the MIT License.
