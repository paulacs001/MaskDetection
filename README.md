# Mask Detection
In this project, CNN are used in order to create a mask-classifier. Given an input image of a face, it classifies between it wearing or not a mask. 
Limited data is available for these purpouses, and mainly related to Chineese subjects, so could prove to be ungeneralizable.

The approach taken uses existing un-masked face datasets, and using the code from MaskTheFace, virtually overlays a mask. To do this, the image is converted to 3D, then the mask is applied, and lastly the image is converted back to 2D.

The results are promising, although many limitations are present in this approach.

***For further reading:***
> Research paper and evaluation is available in the Repository
