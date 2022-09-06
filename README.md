# Segmentation Example
The Jupyter notebook in this repository is a simple example of segmenting a high spatial resolution image using PyShepSeg.

It will take an input image like this:
![image](https://user-images.githubusercontent.com/1754742/188751952-9925255d-a2b6-4748-a1df-778e1e742333.png)

And generate segments around similar objects at a scale determined by the user. This example uses a 10000 pixels minimum size.
![image](https://user-images.githubusercontent.com/1754742/188752052-4fd9187a-445f-4cb8-9c0b-d9977fec5556.png)

The library can also efficiently calculate per segment statistics, such as the mean of each segment:
![image](https://user-images.githubusercontent.com/1754742/188752082-b2e3c821-e2cc-437f-8ab4-92a7b9bf35b3.png)
