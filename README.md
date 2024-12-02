# Supplemental Material for Leveraging Color Channel Independence for Improved Unsupervised Object Detection.
This directory adds supplement materials for the ICLR 2025 submission, "Leveraging Color Channel Independence for Improved Unsupervised Object Detection." We visualize feature maps of the Clevr and Clevrtex datasets for unsupervised OCRL obtained from different target color spaces.

# Structure

At the root directory, there are folders for two datasets:
 - Clevr (folder Clevr)
 - Clevrtex (folder Clevrtex) 
For quick reference, those directories contain overview figures, with the higher resolution raw figures in each subdirectory. Additionally, there are folders labeled e.g. "clevr_0" for the first sample of the Clevr dataset with high-resolution images.

 In each subfolder, the following files can be found:
- "clevr_0_image.png" for the original image
- "clevr_0_RGB_mask.png" for the masks of the color spaces. The HSV and RGB-S masks are also provided
- "clevr_0_gt_mask.png" for the ground truth mask of the scenes
- "clevr_0_HSV - Layer_1.png" for the feature map of layer one on the HSV space.
