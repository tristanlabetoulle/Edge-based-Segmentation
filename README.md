# Edge-based-Segmentation
This is the implementation of a robust method for an segmentation based on edges


## Demo

[![Edge-based segmentation](http://img.youtube.com/vi/IfoXVUk_Gik/0.jpg)](https://youtu.be/IfoXVUk_Gik)

## How to use

You need to install Scilab first. Then :

1.Choose the picture you want to process
	
	Save the picture in the folder 'C:\im_segmentation\' ( you can modify it at line 82 of segmentation_picture )
	Modify the picture on GIMP for instance to get a closed edge for your object.
	Cnvert the picture in black and white using IMLAB for instance

2.Adjust the parameters of the picture
	
	Adjust the gaussian filter parameter and the speed, using "processing_picture" ( Gauss filter then Sobel filter and speed, the edges must be well defined)
	
3.Adjust the parameters of the software	
	
	initialization : to be determined thanks to the matrix of the picture in IMLAB
	INF : you should put about 100 and you can adjust it afterwards
	bruit : see previous step
	sigma : see previous step
