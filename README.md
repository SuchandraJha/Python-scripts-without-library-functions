# Python-scripts-without-library-functions
This repositry contains some well-known algorithms and some other stuffs which I have implemented without using library functions.

PROGRAM NUMBER 1. Linear-regression:
This python script performs linear regression without using library function. The data is predefined. Which can be replaced by any other database or user input data.

----------------------------------------------------------------------------------------------------------------

PROGRAM NUMBER 2. K-means on 3D:
Applying k-means clustering algorithm on 3-dimension without using library function. Number of clusters is given as input by the user. The data is a random predefined dataset, which is broken into 3 lists and plotted in 3 axes. The final clusters can be seen in different colours. For k<=10, the code runs properly. For k>10, the clusters cannot be distinguished by colours. This can be overcomed by adding more colours before plotting, if required.

----------------------------------------------------------------------------------------------------------------

PROGRAM NUMBER 3. Histogram:
An image is taken and it's intensities are found out by the following steps:

i. Download GIMP software (for free). Here's a link: https://www.gimp.org/downloads/

ii. Open the image in GIMP software.

iii. File -> Export As -> Select name of the file and add 'ppm' as file extension -> Export -> Select data formatting as 'ASCII' -> Export

iv. Now select this exported file -> Open With -> Notepad

v. The third row gives rows*columns

vi. From forth line, it gives the intensities in the form: R value for pixel1, G value for pixel1, B value for pixel 1, R value for pixel2, G value for pixel2.......

In this program, I have saved this txt file as 'txtImage6'
Also, note the file path given in the first cell and edit it according to your image location.

The first graph gives the histogram of original image. The second graph gives equalised histogram.
The equalised image is saved as 'newfile.txt' in the same folder where Anaconda software is (C drive).
Select 'newfile.txt' -> Open with GIMP (Now you can see the equalised image).

Bonus tips:
i. Use a low contrast image to see the difference clearly.

ii. Open original and new image side-by-side in GIMP to see the difference.

----------------------------------------------------------------------------------------------------------------------------

PROGRAM NUMBER 4. KNN classification on BC dataset:
A dataset DS_BC is taken which provides medical data on breast cancer.
In this program, I have considered radius and smoothness of tumors, to classify it as benign or malignant.
The dataset is manually divided into training and testing data (as given by user).
The value of 'k' for KNN classification is also entered by the user.
Then each of the test data is classified as benign or malignant, as per algorithm.
Finally the performance of the model is measured.

Disadvantage: Since the dataset is manually divided into test and train data, the consecutive rows from the beginning are taken as train data.
The remaining rows at the bottom are used as test data.
This should not be done and the dataset should be divided randomly.

-------------------------------------------------------------------------------------------------------------------------------

PROGRAM NUMBER 5: K-means clustering on image:
Similar to applying k-means on 3D, it is applied on an image.
The R, G and B components of each pixel is taken as the three axes.
The number of clusters is taken as input and k-means algorithm is applied (without library functions).
The final output shows segmented image, in 'k' segments.
