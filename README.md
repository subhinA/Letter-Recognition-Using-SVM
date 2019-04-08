# Letter-Recognition-Using-SVM
It contains the 26 English alphabets as classes, so it's a multi class classification problem with 26 classes. The data set is taken from the UCI repository. Each row in the data set represents an image of a handwritten alphabet, as shown in figure 1(A). Using some basic image processing, the images are converted into m X n pixels (figure 1(B)), where m and n depend on the size and resolution of the original image. Each pixel contains numeric values, with higher values denoting the presence of dense 'ink'. In the pixels where nothing is written, the pixel value is 0.     A pixel is called 'on' if it contains to a positive numeric value, else it is called 'off'.     Using the pixelated images, 16 features are derived for each image, such as the width of the box, the ratio of the mean variance of x divided by the width of the box, etc.  
