# GRIP-Dataset
Original GRIP Dataset was published in
Please cite the following paper if you use this dataset 

This dataset is modified version of the dataset and contains the following files
1. Original images, in addition to images that post processed using 6 operation; JPEG Compression 
3. Forged images 
4. Black and White ground-truth 
5. Color ground-truth
6.

Images naming follows the (N_M_O) scheme, where N represents a three-digit image number. M denotes image type in which “O represents the original image, F: forged image, B: black and white binary mask, and R: colored ground-truth mask.” O represents the applied post-processed operation on the image and has one of the following combinations “QF: JPEG compression with a specified quality factor, VA: noise additive with a specified variance, AF: blurring by an average filter with a specified size, CA: contrast adjustment with a specified upper bound, BA: brightness adjustment with a specified constant value, and CL: color quantization by a specified intensity level” followed by the parameter used in Table ‎4.1. 