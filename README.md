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

