# Banana-360: A dataset of images containing bananas #


## Dataset properties ##

Total number of images: 82213.

Training set size: 61488 images (one fruit per image).

Test set size: 20622 images (one fruit per image).

Multi-fruits set size: 103 images (more than one fruit per image)

Image size: 100x100 pixels.

Filename format: imageIndex_100.jpg (e.g. 32_100.jpg) or rImageIndex_100.jpg (e.g. r_32_100.jpg) or r2ImageIndex_100.jpg or r3ImageIndex_100.jpg. "r" stands for rotated fruit. "r2" means that the fruit was rotated around the 3rd axis. "100" comes from image size (100x100 pixels).


## Repository structure ##

Folders [Training] and [Test] contain images for training and testing purposes.

Folder [test-multiple_fruits] contains images with multiple fruits. Some of them are partially covered by other fruits. This is an excelent test for real-world detection.


