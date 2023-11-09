# PCA-Implementation-from-Scratch-using-Coloredimage
- Compress a colored image using PCA, then visualize the compresses image

  
- ![R](https://github.com/sahar-hamdi/PCA-Implementation-from-Scratch-using-Coloredimage/assets/93557883/11d56360-afac-4d66-a968-d78f3804f748)


- Decompress the compressed image and visualize it



1- Load the image and convert it to a NumPy array

2- Image Pre-proccessing and Normalization:

         -Normalization
         -Reshape the image
         -calculate mean and standard deviation for image Standardization
         

3- PCA Impelementation From Scratch:

         * 1- calculate the image mean
         * 2- calculate the coveriance of the image
         * 3- Calculate the standard Deviation
         * 4- Calculate Eigenvalues and EigenVetors then sort them to get the maximum eigenvalue.

4- Project the image array:

        -determine the number of PCA Components
        -subtract the image array from image mean
        -get the dot product of image projected and sorted eigenvectors


5- Compress The Projected image

6- Decompress the compressed image array:

         -Project the decompressed image array back onto the original image space
         -Add the mean back to the decompressed image array
         -Convert the decompressed image array back to a NumPy array

  7- Ploting of The Original, Compressed, and Decompressed images.

