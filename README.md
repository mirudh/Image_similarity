Structural Similarity (SSIM) Index is an image quality metric. SSIM index is computed for the image with respect to the reference image. The reference image is usually needs to be of perfect quality.
The structural similarity index measure (SSIM) is a method for predicting the perceived quality of digital television and cinematic pictures, as well as other kinds of digital images and videos. It is also used for measuring the similarity between two images. The SSIM index is a full reference metric; in other words, the measurement or prediction of image quality is based on an initial uncompressed or distortion-free image as reference. SSIM is a perception-based model that considers image degradation as perceived change in structural information, while also incorporating important perceptual phenomena, including both luminance masking and contrast masking terms. The difference with other techniques such as MSE or PSNR is that these approaches estimate absolute errors. Structural information is the idea that the pixels have strong inter-dependencies especially when they are spatially close. These dependencies carry important information about the structure of the objects in the visual scene. Luminance masking is a phenomenon whereby image distortions (in this context) tend to be less visible in bright regions, while contrast masking is a phenomenon whereby distortions become less visible where there is significant activity or "texture" in the image.

**Installing the dependencies**

Create a virtual environment using the following code:

--> python -m venv sim_vnv

Install the below packages using 'pip install' command

1. Scikit image
2. opencv-python
3. numpy

**Testing**

Run the jupyter notebook 

==============================================
Note: Give 2 input images, as specified in the code. 
Your output will be saved in the directory you specify. 
==============================================
