# Imaginary-space-based-on-WGAN
Generate unreal space photos based on GAN. This project originated from the author's interest in space exploration and the computing profession during his college years. 


Toolkit：
1.	Python 3.7.3 (Tailoring and collection of data sets)
2.	PyCharm 2021.1.1 professional edition (Project model training)
3.	Pip (Python Package Index)
4.	tensorflow 1.13.2 (Building a neural network)
5.	numpy 1.16.4 (Matrix calculation)

The collection method of the data set is usually to crawl a large number of data pictures on the website through a python crawler and form a large number of pictures with the same pixel after cropping. After careful consideration, the author decided to download a 40000*30000 pixel (occupies storage space 3.9GB) starry sky image from the Hubble Telescope through NASA’s official website. By cropping this high-pixel image, the image was cropped to approximately 1,2900 photos of the starry sky with 250*250 pixels. The 1,2900 photos are used as the training data set and put into the training model for training.
Original data picture download link: 3.9G version (40000*30000)
http://www.eso.org/public/archives/images/publicationtiff40k/eso1242a.tif 
---------------------------------------------------------------------------------------------------------------
Currently running this item, please check the path where you saved the picture, during the cropping process.

This project is only used for learning and research, and will not be used for commercial activities. If the interests of the original author are violated, please contact me as soon as possible.
