# FGT_segmentation

This repository contains the trained network weights for deep-learning based segmentation of the breast parenchyma in T1-weighted breast MRI, used in the Radiology-published study "Assessing Quantitative Parenchymal Features on Baseline Dynamic Contrast-enhanced MRI and Cancer Occurrence in Women with Extremely Dense Breasts". 

Please note that the deep-learning network has been trained specifically on MRI scans of women aged 50-75 years old with extremely dense breasts from the Dutch national screening programme. Results may vary when applied to to other populations. If you use these network weights, please cite our publication:

> H. Wang, B.H.M. van der Velden, E. Verburg, M.F. Bakker, R.M. Pijnappel, W.B. Veldhuis, C.H. van Gils, K.G.A. Gilhuijs, Assessing Quantitative Parenchymal Features on Baseline Dynamic Contrast-enhanced MRI and Cancer Occurrence in Women with Extremely Dense Breasts, Radiology 2023

## Usage

Clone the git repository in your nnU-Net results folder. Two task IDs are included, one for breast MRIs without fat suppression (Task 650) and one for breast MRIs with fat suppression (Task 651). You can then use the weights like any other nnU-Net. For more information on how to use nnU-Net, see https://github.com/MIC-DKFZ/nnUNet

**UPDATE:** Due to the size of the network we share the trained network weights via the secure servers of the cooperative association of Dutch educational and research institutions, please use this link for Task 650 https://surfdrive.surf.nl/files/index.php/s/L24BQNZZEncqtJP and this link for Task 651 https://surfdrive.surf.nl/files/index.php/s/pRoFiowB0D0TGoY

The network assumes only one channel: the pre-contrast MRI.

For more details regarding applicability of these network weights, we refer to our paper above, as well as for detailed information regarding the training and testing sets. Feel free to reach out with any questions.
