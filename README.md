# FGT_segmentation

This repository contains the trained network weights for the Radiology paper "Assessing Quantitative Parenchymal Features on Baseline Dynamic Contrast-enhanced MRI and Cancer Occurrence in Women with Extremely Dense Breasts". If you use these network weights, please cite our publication:

> Wang, Velden, etc. Gilhuijs, Assessing Quantitative Parenchymal Features on Baseline Dynamic Contrast-enhanced MRI and Cancer Occurrence in Women with Extremely Dense Breasts

## Usage

Clone the git repository in your nnU-Net results folder. Two task IDs are included, one for breast MRIs without fat suppression (Task 650) and one for breast MRIs with fat suppression (Task 651). You can then use the weights like any other nnU-Net. For more information on how to use nnU-Net, see https://github.com/MIC-DKFZ/nnUNet

The network assumes only channel: the pre-contrast MRI.

For more details regarding applicabilty of these network weights, we refer to our paper for more information regarding the training and testing sets. Feel free to reach out if there's any questions.
