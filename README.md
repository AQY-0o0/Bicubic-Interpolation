# Bicubic-Interpolation using python

This Repository contain python code to apply Bi-cubic Interpolation on images. It can aslo be used as a tool to increase input images size to desired one.
Python file **`bicubic_interpolation.py`** contains the code for Bi-cubic Interpolation of the given image.

## Requirements:
`Python 2 or 3`\
`Numpy`\
`matplotlib`\
`imageio`

## How to run code:
If you want to run this code for your own image then you need to place the address of image inside the file **`bicubic_interpolation.py`** and replace **`'Low_Res_Image.jpg'`** with the address of your image and also need to specify how much scaling factor you want. for the scaling factor replace **Scaling_factor = 4** with your desired number but remember it must be in order of 2, 4, 8, 16 etc.

Running the code will also save output image named as `New_Image.jpg`.

### Bicubic-Interpolation with different scaling:
![image text](https://github.com/Mubashir-ul-Islam/Bicubic-Interpolation/blob/master/media/Comparison_of_Resolution.jpg)

### Scaling Comparison:
![image text](https://github.com/Mubashir-ul-Islam/Bicubic-Interpolation/blob/master/media/Scaling.jpg)
