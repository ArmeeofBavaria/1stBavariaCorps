## About Medical Data
There are 10 DIXCTW files, with image data from CT, T1, and T2.

Our current task is to prepare the data/images for GAN network, which will transform 3 modalities of T2 (water, fat-only, in-phase) to T1 images.

### T1 image demontration:




## Image Segmentation - Construct 3D part from the medical image file.
######ITK-SNAP provided a set of algorithm for segmentation.
* Pick a seed (an area on the 3D image)
* Add bubble to the images
* Segmentation will start(It will automatically fill in the gap between these bubbles)

## Image Slicing using SimpleITK

