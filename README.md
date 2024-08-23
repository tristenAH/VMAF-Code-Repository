# VMAF Code Repository

## Description of the repository:
This repository contains all VMAF code involved with the ongoing video motion transfer project and the background code required to run it. For more information on the contents unrelated to VMAF, please see the Motion-Transfer-Keypoints-Prediction GitHub on which this is based (https://github.com/xuebai95/Motion-Transfer-Keypoints-Prediction).

## Directory Contents:
**The Keypoints_Prediction folder** has files to generate predicted videos using the various algorithms (VRNN, RNN, VAE, No Prediction), to run VMAF on them, and generate visualizations of the VMAF data.

The environment_setup file in the Keypoints_Prediction folder is a text file which details what you have to do in order to be able to run the notebooks in the same folder.

The log directory is for the generated images, videos, and VMAF outputs produced by the notebooks in the Keypoints_Prediction folder.

## Large Files and where to put them 
Checkpoints for the FOMM model trained on the VoxCeleb dataset can be found under this google drive link.
https://drive.google.com/drive/folders/1pachVtWHibzDi3E61jUmqFfz2hVxA1GX?usp=drive_link.
The keypoints for training a RNN, VAE, or VRNN model are on the VoxCeleb dataset are also found in the same link.
Please place the vox-cpk.pth.tar file in the "Training_Prediction/FOMM/Trained_Models/" folder.

Other large files can be found in this google drive link:
https://drive.google.com/drive/u/0/folders/11slLV8bRr0ViinzeCGZZMNPKsCMn33tx
Place both files beginning with "VRNN_3883videos ..." and both .pth files in the "Keypoints_Prediction/Checkpoints/" folder.
Place both .pkl files and the "VMAF_Algorithm_Comparison.ipynb" file in the "Keypoints_Prediction/" folder.
Finally, place "VMAF_Algorithm_Comparison-checkpoint.ipynb" in the "Keypoints_Prediction/.ipynb_checkpoints/" folder.
