---
layout: page
title: Dataset
---

## Train Dataset

- The dataset contains 1447 subjects of whole-body 18F-FDG PET imaging, acquired from Siemens Biograph Vision Quadra (n=387) and United Imaging uEXPLORER (n=1060).
- All data was acquired in list mode allowing for a rebinding of data to simulate different acquisition times. Each simulated low statistics corresponding to low dose PET with a certain dose reduction factor (DRF) was reconstructed from the counts of a time window resampled at the middle of the acquisition with correspondingly reduced time. Low statistics corresponding to low dose image will be provided with DRF at 4, 10, 20, 50 and 100, as well as full dose image. All these low-dose PET are produced by subsampling a portion of the full scan, so they should be perfectly aligned with the full dose PET.

## Test Dataset

Held out 50 subjects scanned with Siemens Biograph Vision Quadra and United Imaging uEXPLORER

## Download

To access the data, please first download the Data Transfer Agreement (DTA) from the link below:

<!-- [https://drive.google.com/file/d/1fJoeGNSAO9GFqWHoQn5T2WBBBwtOosXm/view?usp=sharing](https://drive.google.com/file/d/1fJoeGNSAO9GFqWHoQn5T2WBBBwtOosXm/view?usp=sharing)   -->
[https://drive.google.com/file/d/1-dGYEB6lWSJeY8eI5XFtT3MtJGOqXAX1/view?usp=sharing](https://drive.google.com/file/d/1-dGYEB6lWSJeY8eI5XFtT3MtJGOqXAX1/view?usp=sharing)

You'll receive the download link for the dataset once you send back the signed DTA to: [yizhou.chen@students.unibe.ch](mailto:yizhou.chen@students.unibe.ch) OR [alejandro.lopez@unibe.ch](mailto:alejandro.lopez@unibe.ch)
<!-- [christoph.clement@students.unibe.ch](mailto:christoph.clement@students.unibe.ch) -->

## Issues

The following cases are wrongly labeled as 18F-FDG. They are 68Ga-DOTA:

Anonymous_ANO_20220224_1711567_102845
Anonymous_ANO_20220224_1709580_104139
Anonymous_ANO_20220224_1707578_105431
Anonymous_ANO_20220224_1705576_110625
Anonymous_ANO_20220224_1703593_111906
Anonymous_ANO_20220224_1701584_113106
Anonymous_ANO_20220224_1713571_101453

In the test dataset:

"Anonymous-06_DRF-50.nii.gz" and "Anonymous-48_DRF-50.nii.gz" are corrupted and have been removed from the test dataset

In the original release of the test dataset, the SliceThickness_mm values for Quadra PET images in the provided csv file were incorrect. This has been corrected in the same link for the download but please, make sure you have the right csv.



