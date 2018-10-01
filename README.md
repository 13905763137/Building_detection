# Building_detection
This project is to identify buildings in satellite using Unet and masking method

To execute this project, please follow the below guidlines

1: run_code.py is the main file

2: save images and polygon files in images and polygon folders under data

3: ProcessFile class is invoked in run_code that creates csv files of images and masks with user define pixel values like 128, 256 etc.

4: Processed image csv and mask csv files are used in main code to build model 

# references
https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/

https://github.com/zhixuhao/unet

https://arxiv.org/pdf/1602.06564v1.pdf

http://cs229.stanford.edu/proj2017/final-reports/5243715.pdf

# output 
![Sample Output](https://github.com/statisticalplumber/Building_detection/blob/master/sample_output.PNG)
