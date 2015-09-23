#Beautiful Crop Image
**_This is project edit on timthumb project_**

Because default timthumb crop image by center, some image will not beautiful after crop (ex: __picture of human__).

[Demo Link](https://www.vietstar.net)

![Demo Image](https://media-vietstar.cdn.vccloud.vn/source/demo/crop-image.jpg "Demo Image")

How to used
-------
_**Beautiful Crop Image** use same Timthumb_

Basic example with minimum parameters. Automatically resizes to 100 x 100:
	
	crop-image.php?src=source/test.jpg

High quality = awesome image:
	
	crop-image.php?src=source/test.jpg&q=100

Specify the width only and the **height** will change to be relatively sized to keep the picture in proportion:
	
	crop-image.php?src=source/test.jpg&w=500

Specify the height only and the **width** will change to be relatively sized to keep the picture in proportion:
	
	crop-image.php?src=source/test.jpg&h=350

Width and Height together:
	
	crop-image.php?src=source/test.jpg&h=350&w=500
	
#### See more at timthumb document