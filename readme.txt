This is a re-implementation of our paper [1] and for non-commercial use only. 

You need to install Matlab and Python (with Tensorflow-GPU and OpenCV packages) to run this code.


Usage:


1. Generating training data: put rainy images into "/data_generation/image/input" and label images into "/data_generation/image/label". Note that pair images' names must be the same.

2. Open MATLAB and direct to "/data_generation" , run 
"generate_train.m" and "generate_validation.m" to generate training and validation data, respectively.

 The h5 files should be generated at "/data_generation/h5data".

3. Run 
"training.py" for training and trained models should be generated at "/model".

4. After training, run 
"testing.py" to test new images.


We release our rainy image dataset at: http://smartdsp.xmu.edu.cn/cvpr2017.html. 


If this code and dataset help your research, please cite our related papers:

[1] X. Fu, J. Huang, D. Zeng, Y. Huang, X. Ding and J. Paisley. ¡°Removing Rain from Single Images via a Deep Detail Network¡±, CVPR, 2017.

[2] X. Fu, J. Huang, X. Ding, Y. Liao and J. Paisley. ¡°Clearing the Skies: A deep network architecture for single-image rain removal¡±, IEEE Transactions on Image Processing, 2017.



Welcome to our homepage: http://smartdsp.xmu.edu.cn/



