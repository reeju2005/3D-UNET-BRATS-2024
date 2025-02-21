# 3D-UNET-BRATS-2024
This is the 3D Unet and YOLOv8 architecture for BRATS 2024.
Steps to run it:
1. Setup environment: All the necessary packages are being initialised. Preferably use Jupyter notebook. 
The dataset is downloaded from https://www.synapse.org/Synapse:syn53708249/wiki/626323
2. Image data descriptions
All BraTS multimodal scans are available as NIfTI files (.nii.gz) -> commonly used medical imaging format to store brain imaging data obtained using MRI and describe different MRI settings
T1: T1-weighted, native image, sagit
T1c: T1-weighted, contrast-enhanced (Gadolinium) image, with 3D acquisition and 1 mm isotropic voxel size for most patients.
T2: T2-weighted image, axial 2D acquisition, with 2–6 mm slice thickness.
FLAIR: T2-weighted FLAIR image, axial, coronal, or sagittal 2D acquisitions, 2–6 mm slice thickness.
Data were acquired from the BraTS 2024 dataset in https://www.synapse.org/Synapse:syn53708249/wiki/626323\

I wish to bring to everyone's attention several flaws in the execution of the project, which would require the help of other, more qualified persons. If they can offer solutions to this problems, I shall incorporate them in the repository and will be eternally grateful to them.
1. The dimensions of the 3D Unet model and that of the test images do not match with each other. This leads to errors during model training.
2. The YOLOv8 model due to some reason cannot load the data during model training.



