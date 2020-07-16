# Image-Quality-Analysis
A machine learning model for determining quality of remote sensing satellite images.


In this project, an automatic approach for detecting quality of remote sensing RE
SOURCESAT - 2A satellite images has been introduced. RESOURCESAT-2 series satellite images are used for urban planning, crop monitoring, ﬁnding vegetation index etc., so for these applications the quality of an image depends on amount of land present in the images. Image quality detection is helpful to scientists in improving the accuracy of land cover classiﬁcation in satellite images. This algorithm is a Deep Learning Convolutional Neural Network model trained on RESOURCESAT-2A LISS4 satellite images using Inception V3 transfer learning. The objective is to accurately predict quality of optical satellite images by rating them in categories from lowest to highest according to the land cover. This project has one CNN model trained on the available data set, it will classify images among 5 categories:

Rating 1-5:
1 - image with no land
2 - 1/4 th image with visible land features
3 - 2/4 th image with land feature
4 - images with 3/4 th or more land coverage
5 - image with only land features
