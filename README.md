# image-enhancement-clahe

dataset can be found on:
CHASE-DB1 : https://blogs.kingston.ac.uk/retinal/chasedb1/
STARE : https://cecas.clemson.edu/~ahoover/stare/

Here we compare Histogram Equalization with Contrast Limited Adaptive Histogram Equalization (CLAHE) on CHASE-DB1 and STARE dataset to see which algorihm is better at enhance low radiance retinal image. CLAHE was applied on R-channel. Measurement of noise in images is done with Peak Signal-to-Noise Ratio (PSNR) method. The higher the PSNR, the better the quality of the compressed, or reconstructed image. The experimental results show that CLAHE with tile 16x32 has higher PSNR value on the image CHASE-DB1 dataset with a PSNR value = 32.22.
